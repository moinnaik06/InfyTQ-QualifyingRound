In MySQL, you can find all SQL standard numeric types including exact number data type and approximate numeric data types including integer, fixed-point and floating-point. In addition, MySQL also has BIT data type for storing bit values. Numeric types can be signed or unsigned except for the BIT type.

The following table shows the summary of numeric types in MySQL:

Numeric Types	Description
TINYINT - A very small integer
 SMALLINT	- A small integer
 MEDIUMINT - A medium-sized integer
 INT - A standard integer
 BIGINT - A large integer
 DECIMAL - A fixed-point number
 FLOAT - A single-precision floating point number
 DOUBLE - A double-precision floating point number
 BIT - A bit field
MySQL Boolean data type
MySQL does not have the built-in BOOLEAN or BOOL data type. To represent boolean values, MySQL uses the smallest integer type which is TINYINT(1). In other words, BOOLEAN and BOOL are synonyms for TINYINT(1).

MySQL String data types
In MySQL, a string can hold anything from plain text to binary data such as images or files. Strings can be compared and searched based on pattern matching by using the LIKE operator, regular expression, and full-text search.

The following table shows the string data types in MySQL:

String Types	Description
 CHAR	A fixed-length nonbinary (character) string
 VARCHAR	A variable-length non-binary string
 BINARY	A fixed-length binary string
 VARBINARY	A variable-length binary string
 TINYBLOB	A very small BLOB (binary large object)
 BLOB	A small BLOB
 MEDIUMBLOB	A medium-sized BLOB
 LONGBLOB	A large BLOB
 TINYTEXT	A very small non-binary string
 TEXT	A small non-binary string
 MEDIUMTEXT	A medium-sized non-binary string
 LONGTEXT	A large non-binary string
 ENUM	An enumeration; each column value may be assigned one enumeration member
 SET	A set; each column value may be assigned zero or more SET members
MySQL date and time data types
MySQL provides types for date and time as well as the combination of date and time. In addition, MySQL supports the timestamp data type for tracking the changes in a row of a table. If you just want to store years without dates and months, you can use the YEAR data type.

The following table illustrates the MySQL date and time data types:

Date and Time Types	Description
 DATE	A date value in CCYY-MM-DD format
 TIME	A time value in hh:mm:ss format
 DATETIME	A date and time value inCCYY-MM-DD hh:mm:ssformat
 TIMESTAMP	A timestamp value in CCYY-MM-DD hh:mm:ss format
 YEAR	A year value in CCYY or YY format
MySQL spatial data types
MySQL supports many spatial data types that contain various kinds of geometrical and geographical values as shown in the following table:

Spatial Data Types	Description
 GEOMETRY	A spatial value of any type
 POINT	A point (a pair of X-Y coordinates)
 LINESTRING	A curve (one or more POINT values)
 POLYGON	A polygon
 GEOMETRYCOLLECTION	A collection of GEOMETRYvalues
 MULTILINESTRING	A collection of LINESTRINGvalues
 MULTIPOINT	A collection of POINTvalues
 MULTIPOLYGON	A collection of POLYGONvalues
JSON data type
MySQL supported a native JSON data type since version 5.7.8 that allows you to store and manage JSON documents more effectively. The native JSON data type provides automatic validation of JSON documents and optimal storage format.
