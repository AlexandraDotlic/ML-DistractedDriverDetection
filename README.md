# Detekcija vozačeve nepažnje

Autor: Aleksandra Dotlić 1077/2020

Tema ovog rada je detekcija vozačeve nepažnje. Koristi se skup podataka koji se sastoji od slika kategorizovanih u 10 različitih klasa - devet različitih nepažljivih aktivnosti (vozač razgovara telefonom,
kuca sms poruku, gleda iza sebe, jede, šminka se i slično) i jedna aktivnost koja demonstrira sigurnu vožnju. Cilj je na svakoj slici predvideti verovatnoću onoga što vozač radi.
Skup podataka je dostupan na adresi https://www.kaggle.com/c/state-farm-distracted-driver-detection/data .

Ideja je da se kreira model visoke tačnosti u cilju razlikovanja bezbedne od nebezbedne vožnje. Prvo je izvršena obrada ulaznih podataka (slika) kako bismo dobili ulazne vektore. Kao osnovni model uzeta je metoda slučajnih šuma, a kao glavni model uzeta je konvolutivna neuronska mreža. Oba modela daju dobre rezultate pri čemu je tačnost drugog modela nešto veća.


Korišćena literatura: 

http://ml.matf.bg.ac.rs/readings/ml.pdf

https://numpy.org/

https://scikit-learn.org/stable/

https://matplotlib.org/

https://www.tensorflow.org/
