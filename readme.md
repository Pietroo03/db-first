Table name 
- used cars

Table structure
- ID --> BIGINT, AUTO-INCREMENT, (PRIMARY-KEY)
- targa --> CHAR(7), UNIQUE, NOT-NULL
- kilometri --> MEDIUMINT, NOT-NULL
- marca --> VARCHAR(50), NOT-NULL
- modello --> VARCHAR(50), NOT-NULL
- tipologia --> VARCHAR(30), NULL
- anno --> YEAR, NOT-NULL
- colore --> VARCHAR(30), NULL
- posti --> TINYINT, NOT-NULL
- porte --> TINYINT, NOT-NULL
- tipo di combustione --> VARCHAR(30), NOT-NULL
- tipo di cambio --> VARCHAR(30, NOT-NULL)
- incidenti --> CHAR(2), NOT-NULL
- numero incidenti --> TINYINT, NULL
- descrizione incidenti --> VARCHAR(250), NULL
- tipo di trazione --> VARCHAR(30), NOT-NULL