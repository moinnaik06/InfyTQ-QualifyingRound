In MySQL, you can find all SQL standard numeric types including exact number data type and approximate numeric data types including integer, fixed-point and floating-point. In addition, MySQL also has BIT data type for storing bit values. Numeric types can be signed or unsigned except for the BIT type.

The following table shows the summary of numeric types in MySQL:

Numeric Types	Description
1) TINYINT - A very small integer
2) SMALLINT	- A small integer
3) MEDIUMINT - A medium-sized integer
4) INT - A standard integer
5) BIGINT - A large integer
6) DECIMAL - A fixed-point number
7) FLOAT - A single-precision floating point number
8) DOUBLE - A double-precision floating point number
9) BIT - A bit field

A) MySQL Boolean data type
MySQL does not have the built-in BOOLEAN or BOOL data type. To represent boolean values, MySQL uses the smallest integer type which is TINYINT(1). In other words, BOOLEAN and BOOL are synonyms for TINYINT(1).

B) MySQL String data types
In MySQL, a string can hold anything from plain text to binary data such as images or files. Strings can be compared and searched based on pattern matching by using the LIKE operator, regular expression, and full-text search.

The following table shows the string data types in MySQL:

String Types	Description
1) CHAR	A fixed-length nonbinary (character) string
2) VARCHAR	A variable-length non-binary string
3) BINARY	A fixed-length binary string
4) VARBINARY	A variable-length binary string
5) TINYBLOB	A very small BLOB (binary large object)
6) BLOB	A small BLOB
7) MEDIUMBLOB	A medium-sized BLOB
8) LONGBLOB	A large BLOB
9) TINYTEXT	A very small non-binary string
10) TEXT	A small non-binary string
11) MEDIUMTEXT	A medium-sized non-binary string
12) LONGTEXT	A large non-binary string
13) ENUM	An enumeration; each column value may be assigned one enumeration member
14) SET	A set; each column value may be assigned zero or more SET members

C) MySQL date and time data types
MySQL provides types for date and time as well as the combination of date and time. In addition, MySQL supports the timestamp data type for tracking the changes in a row of a table. If you just want to store years without dates and months, you can use the YEAR data type.

The following table illustrates the MySQL date and time data types:

Date and Time Types	Description
1) DATE	A date value in CCYY-MM-DD format
2) TIME	A time value in hh:mm:ss format
3) DATETIME	A date and time value inCCYY-MM-DD hh:mm:ssformat
4) TIMESTAMP	A timestamp value in CCYY-MM-DD hh:mm:ss format
5) YEAR	A year value in CCYY or YY format

D) MySQL spatial data types
MySQL supports many spatial data types that contain various kinds of geometrical and geographical values as shown in the following table:

Spatial Data Types	Description
1) GEOMETRY	A spatial value of any type
2) POINT	A point (a pair of X-Y coordinates)
3) LINESTRING	A curve (one or more POINT values)
4) POLYGON	A polygon
5) GEOMETRYCOLLECTION	A collection of GEOMETRYvalues
6) MULTILINESTRING	A collection of LINESTRINGvalues
7) MULTIPOINT	A collection of POINTvalues
8) MULTIPOLYGON	A collection of POLYGONvalues\
9) JSON data type

MySQL supported a native JSON data type since version 5.7.8 that allows you to store and manage JSON documents more effectively. The native JSON data type provides automatic validation of JSON documents and optimal storage format.
