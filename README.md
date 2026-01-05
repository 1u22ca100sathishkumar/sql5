# sql5
1. String Function

Condition:

Take 2 variables

One for "Language"

One for "Tamil"

Output should be:
LANGUAGE: Tamil

SQL Query
SET @var1 = 'Language';
SET @var2 = 'Tamil';

SELECT CONCAT(UPPER(@var1), ': ', @var2) AS Result;

Output
LANGUAGE: Tamil


Functions used:

UPPER() → converts text to uppercase

CONCAT() → joins strings

2. Extract Day, Month & Year from Today’s Date
SQL Query
SELECT 
    DAY(CURRENT_DATE) AS DAY,
    MONTH(CURRENT_DATE) AS MONTH,
    YEAR(CURRENT_DATE) AS YEAR;

Sample Output
DAY	MONTH	YEAR
5	1	2026

Functions used:

DAY()

MONTH()

YEAR()

CURRENT_DATE
