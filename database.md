[//]: # 'Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.'

# Cars showroom  

## Car models  

* ID                        BIGINT PRIMARY KEY NOTNULL UNIQUE INDEX
* Marca                     VARCHAR(20) NOTNULL INDEX
* Modello                   VARCHAR(50) NOTNULL INDEX
* Prezzo                    DECIMAL(8,2) NOTNULL
* Immatricolazione          DATE NOTNULL 
* Anno                      YEAR NOTNULL INDEX
* Motore                    VARCHAR(255) NOTNULL
* Carburante                VARCHAR(255) NOTNULL
* Alimentazione             VARCHAR(255) NULL
* Cilindrata                SMALL/MEDIUMINTNULL
* Valvole                   TINYINTNULL
* Turbo                     VARCHAR(255) NULL
* Rapporto di compressione  FLOAT(3,1) NULL
* Trazione                  VARCHAR(255) NULL
* Cambio                    VARCHAR(255) NULL
* Autonomia                 SMALL/MEDIUMINTNULL
* Capacità serbatoio        TINYINTNULL
* Velocità Massima          TINYINTNULL
* Tipo di carrozzeria       VARCHAR(255) NULL
* Numero Porte              TINYINT NOTNULL
* Passo                     FLOAT(4,1) NULL




