# Classification-Mobile-Price

Aquest projecte té com a objectiu desenvolupar un classificador de preus de telèfons mòbils basat en diferents característiques tècniques del dispositiu. Utilitza tècniques d’anàlisi de dades, preprocessament, i diversos algoritmes de Machine Learning per predir la categoria de preu d’un mòbil.

### 1. Descripció del projecte

L’objectiu principal és crear un model capaç de predir la categoria de preu d’un telèfon mòbil utilitzant com a entrada les seves especificacions de hardware (RAM, bateria, càmera, resolució, etc.).

El dataset utilitzat està disponible a Kaggle:

Mobile Price Classification Dataset: https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

La variable objectiu (Price_range) té quatre classes:

0 → Baix

1 → Mitjà

2 → Alt

3 → Molt alt

Aquest projecte segueix un flux complet de Machine Learning:

Exploració de dades (EDA)

Preprocessament

Entrenament de models

Avaluació del rendiment

Conclusions i interpretació de resultats

### 2. Dataset

El dataset conté les següents característiques:

ID: identificador del producte (enter)

Battery_power: capacitat de la bateria en mAh (enter)

Blue: compatibilitat amb Bluetooth (0/1)

Clock_speed: velocitat de la CPU en GHz (decimal)

Dual_sim: suport per a doble SIM (0/1)

Fc: resolució de la càmera frontal (MP)

Fourth_gen: compatibilitat amb 4G (0/1)

Int_memory: memòria interna (GB)

M_dep: profunditat del dispositiu (cm)

Mobile_wt: pes del mòbil (grams)

N_cores: nombre de nuclis del processador

Pc: resolució de la càmera posterior (MP)

Px_height: alçada de resolució de pantalla (px)

Px_width: amplada de resolució de pantalla (px)

Ram: memòria RAM (MB)

Sc_h: alçada de la pantalla (polzades)

Sc_w: amplada de la pantalla (polzades)

Talk_time: autonomia màxima de trucada (hores)

Three_g: compatibilitat amb 3G (0/1)

Touch_screen: pantalla tàctil (0/1)

Wifi: connexió WiFi (0/1)

Price_range: etiqueta de preu (0–3)
