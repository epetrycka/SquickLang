## Funkcje SQL
Funkcje które będą zaimplementowane w naszym języku

### Atributes:
* WHERE
* ORDER BY
* GROUP BY
* LIMIT
* HAVING
### DML (Data Manipulation Language):
* SELECT
* INSERT
* UPDATE
* DELETE
* COPY
### DCL (Data Control Language):
* GRANT
* REVOKE
### DDL (Data Definition Language):
* CREATE DATABASE
* CREATE TABLE
* CREATE INDEX
* CREATE VIEW
* CREATE SCHEMA
* CREATE SEQUENCE
* ALTER TABLE
* DROP DATABASE
* DROP TABLE
* DROP INDEX
* DROP VIEW
* DROP SEQUENCE
### Transakcje:
* BEGIN
* COMMIT
* ROLLBACK
* SAVEPOINT
* RELEASE SAVEPOINT
### Funkcje Agregujące:
* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()
* GROUP_CONCAT()
* ARRAY_AGG()
* STRING_AGG()
### Funkcje Okienkowe (Window Functions):
* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* NTILE()
* LEAD()
* LAG()
* FIRST_VALUE()
* LAST_VALUE()
* NTH_VALUE()
* CUME_DIST()
* PERCENT_RANK()
* PERCENTILE_CONT()
* PERCENTILE_DISC()
### Operacje JOIN:
* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN
* CROSS JOIN
* SELF JOIN
### Typy Danych:
* SERIAL
* BIGSERIAL
* TEXT
* VARCHAR
* CHAR
* BOOLEAN
* DATE
* TIMESTAMP
* TIME
* INTERVAL
* UUID
* BYTEA
* JSON
* JSONB
* ARRAY
### Subzapytania:
* IN
* EXISTS
* ANY
* ALL
* ANY / ALL Subqueries
* SELECT INTO
### Funkcje Matematyczne:
* ABS()
* CEIL()
* FLOOR()
* ROUND()
* MOD()
* POWER()
* SQRT()
* EXP()
* LN()
* LOG()
* RADIANS()
* DEGREES()
### Funkcje Tekstowe:
* CONCAT()
* SUBSTRING()
* LENGTH()
* UPPER()
* LOWER()
* TRIM()
* REPLACE()
* POSITION()
* REGEXP_REPLACE()
* REGEXP_MATCH()
* TO_CHAR()
### Funkcje Czasowe:
* CURRENT_DATE
* CURRENT_TIME
* CURRENT_TIMESTAMP
* NOW()
* EXTRACT()
* DATE_TRUNC()
* AGE()
* TO_TIMESTAMP()
* TO_DATE()
* TO_TIME()
* DATE_PART()
### Funkcje Agregujące na JSON:
* JSON_AGG()
* JSON_OBJECT_AGG()
* JSON_BUILD_OBJECT()
* JSON_BUILD_ARRAY()
* JSON_EXTRACT_PATH()
* JSONB_AGG()
* JSONB_OBJECT_AGG()
* JSONB_BUILD_OBJECT()
* JSONB_BUILD_ARRAY()
### Funkcje Przestrzenne (PostGIS):
* ST_AsText()
* ST_GeometryType()
* ST_Distance()
* ST_Within()
* ST_Intersects()
* ST_Contains()
* ST_Buffer()
* ST_Transform()
### Zdarzenia:
* CREATE TRIGGER
* DROP TRIGGER
### Indeksy:
* CREATE INDEX
* DROP INDEX
* GIN INDEX
* GIST INDEX
### Operacje na Użytkownikach i Uprawnieniach:
* CREATE USER
* ALTER USER
* DROP USER
* GRANT
* REVOKE
### Funkcje Rozwiązujące Konflikty:
* ON CONFLICT DO NOTHING
* ON CONFLICT DO UPDATE
### Funkcje Do Obsługi Zasobów:
* EXPLAIN
* VACUUM
* ANALYZE
* REINDEX
### Funkcje Administracyjne:
* SHOW
* SET
* RESET
* SELECT pg_stat_activity()