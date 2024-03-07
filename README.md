# DB-FIRST

## TRACCIA

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## RISOLUZIONE

|        FIELD        |     TYPE     |            ATTRIBUTES            |    INDEX    |
| :-----------------: | :----------: | :------------------------------: | :---------: |
|         id          |     INT      | AUTO_INCREMENT (NOTNULL, UNIQUE) | PRIMARY_KEY |
|    vehicle_image    |     TEXT     |               NULL               |             |
|    vehicle_type     | VARCHAR(10)  |             NOTNULL              |             |
|       vendor        | VARCHAR(15)  |             NOTNULL              |             |
|        model        | VARCHAR(15)  |             NOTNULL              |             |
|        color        | VARCHAR(20)  |             NOTNULL              |             |
|        doors        |   TINYINT    |       NOTNULL, DEFAULT(5)        |             |
|        plate        | VARCHAR(10)  |           NULL, UNIQUE           |             |
|       wheels        |   TINYINT    |       NOTNULL, DEFAULT(4)        |             |
|     gear_number     |   TINYINT    |       NOTNULL, DEFAULT(5)        |             |
|      gear_type      | VARCHAR(15)  |    NOTNULL, DEAFULT('MANUAL')    |             |
|     conditions      |     TEXT     |               NULL               |             |
|   production_year   |     YEAR     |             NOTNULL              |             |
|   starting_price    | DOUBLE(12,2) |             NOTNULL              |             |
| engine_output_type  |   CHAR(2)    |             NOTNULL              |             |
| engine_output_value |    SMALL     |             NOTNULL              |             |
|      fuel_type      | VARCHAR(15)  |             NOTNULL              |             |
