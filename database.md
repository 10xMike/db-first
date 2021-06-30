[//]: # 'Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.'

# Car showroom  

## Car models  

* ID                        BIGINT PRIMARY KEY NOTNULL UNIQUE INDEX
* Marca                     VARCHAR(255) NOT NULL
* Modello                   VARCHAR(255) NOT NULL 
* Prezzo                    DECIMAL(8,2) NOT NULL
* Immatricolazione          DATE NOT NULL
* Anno                      YEAR NOT NULL
* Motore                    VARCHAR(255) NOT NULL
* Carburante                VARCHAR(255) NOT NULL
* Alimentazione             VARCHAR(255) NULL
* Cilindrata                SMALL/MEDIUMINT NULL
* Valvole                   TINYINT NULL
* Turbo                     VARCHAR(255) NULL
* Rapporto di compressione  FLOAT(3,1) NULL
* Trazione                  VARCHAR(255) NULL
* Cambio                    VARCHAR(255) NULL
* Autonomia                 SMALL/MEDIUMINT NULL
* Capacità serbatoio        TINYINT NULL
* Velocità Massima          TINYINT NULL
* Tipo di carrozzeria       VARCHAR(255) NULL
* Numero Porte              TINYINT NOT NULL
* Passo                     FLOAT(4,1) NULL




