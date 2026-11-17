# Orles UPF

Repositori per executar el sistema de votació de les Orles de les Enginyeries de les Tecnologies de la Informació i la Comunicació (TIC) de la Universitat Pompeu Fabra (UPF).

El primer curs que es va aplicar aquest sistema va ser pels graduats el curs acadèmic 2025-26. Es van votar els professors per als quatre graus d'Enginyeries TIC: en Sistemes Audiovisuals, en Ciència de Dades, en Informàtica i en Xarxes de Telecomunicacions. El mateix sistema servia per a votar el top-16 de professors del grau, com el top-18 de professors de l'agrupació dels graus, sense incloure el degà, el qual sempre apareix a les orles. El sistema va ser desenvolupat pel mateix delegat d'Enginyeria de Dades de 4t curs d'aquell any, Marc Bosch Manzano.

El mateix repositori pot ser escalable a qualsevol any, grau o agrupació de graus, si es fa la selecció de professors adient, assignatures i graus, i se'n proporcionen les seves informacions i imatges.

- @autor: Marc Bosch Manzano
- @creació: 03/05/2026

## Esquema de Fitxers

```
orles-upf/
│
├── app.py                # Punt d'entrada de la web de votacions.
├── common.py             # Definicions de constants i utilitats compartides entre els scripts.
├── preprocess.py         # Compilació de les dades per a la votació per la creació d'un rànquing de professors.
├── postprocess.py        # Generació de les estadístiques de les votacions.
│
├── data/                 # Informació dels professors (.csv) i votacions de l'alumnat (.json) de la web.
│
├── static/
│   └── imatges/          # Imatges dels professors a ser votats (.png, .jpg)
│
└── templates/
    ├── index.html        # Selecció dels candidats a votar.
    └── return.html       # Confirmació de la votació.
```
