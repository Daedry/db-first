Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

# Dealership

## Modello: used Car

## Table: used Cars

- id :               BIGINT        PRIMARY
- brand :            VARCHAR(20)   NOTNULL
- model :            VARCHAR(20)   NOTNULL, UNIQUE
- year :             YEAR          NOTNULL
- km_traveled :      FLOAT(6, 0)   NULL
- overhauled :       TINYINT       NULL
- price :            FLOAT(7, 0)   NOTNULL
