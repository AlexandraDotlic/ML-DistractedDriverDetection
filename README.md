# Detekcija vozačeve nepažnje

Autor: Aleksandra Dotlić 1077/2020

Tema ovog rada je detekcija vozačeve nepažnje. Koristi se skup podataka koji se sastoji od slika kategorizovanih u 10 različitih klasa - devet različitih nepažljivih aktivnosti ( vozač razgovar telefonom,
kuca sms poruku, gleda iza sebe, jede, šminka se i slično) i jedna aktivnost koja demonstrira sigurnu vožnju. Cilj je na svakoj slici predvideti verovatnoću onoga što vozač radi.
Skup podataka je dostupan na adresi https://www.kaggle.com/c/state-farm-distracted-driver-detection/data .

Ideja je kreiranje modela visoke tačnosti kako bismo razlikovali bezbednu od nebezbedne vožnje. Prvo je izvršena obrada ulaznih podataka (slika) kako bismo dobili ulazne vektore
a zatim su iskorišćeni klasifikatori (slučajne šume i konvolutivna neuronska mreža) za predviđanje tipa aktivnosti vozača. 
Uspešno su implementiran i model slučajnih šuma i konvolutivna neuronska mreža od kojih je drugi dao nešto bolji rezultat.


Korišćena literatura: 

http://ml.matf.bg.ac.rs/readings/ml.pdf

https://numpy.org/

https://scikit-learn.org/stable/

https://matplotlib.org/

https://www.tensorflow.org/
