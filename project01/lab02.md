# Konwersja wytrenowanych sieci do modelu Open Neural Network Exchange (ONNX) i wykorzystanie ich w UNITY przy użyciu Barracuda
## Metody głębokiego uczenia w systemach wizyjnych i wirtualnej rzeczywistości

- Maksymalna liczba punktów: 10
- Skala ocen za punkty:
    - 9-10 ~ bardzo dobry (5.0)
    - 8 ~ plus dobry (4.5)
    - 7 ~ dobry (4.0)
    - 6 ~ plus dostateczny (3.5)
    - 5 ~ dostateczny (3.0)
    - 0-4 ~ niedostateczny (2.0)

Na tym laboratorium zapoznamy się ze sposobem integrowania wytrenowanej od podstaw sieci DNN z frameworkiem Unity poprzez modele ONNX oraz bibliotekę Barracuda.

Do rozwiązania laboratorium można używać wszystkich kodów źródłowych z wykładów.

1. [5 punktów] Wytrenuj sieć neuronową klasyfikującą obrazy psów i kotów. Link do zbioru treningowego i walidacyjnego: [link](https://aghedupl-my.sharepoint.com/personal/thachaj_agh_edu_pl/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fthachaj%5Fagh%5Fedu%5Fpl%2FDocuments%2FMGU%5Flab%2Fcats%5Fand%5Fdogs%5Ffiltered%2Ezip&parent=%2Fpersonal%2Fthachaj%5Fagh%5Fedu%5Fpl%2FDocuments%2FMGU%5Flab&ga=1). Określ skuteczność[link zapasowy](https://www.dropbox.com/scl/fi/xbk62pxwj021mwkfl2f8s/cats_and_dogs_filtered.zip?rlkey=othb4fkmxtldd5b7cnu0xwdjy&st=6iyz7rcp&dl=0) klasyfikacji modelu. Wyeksportuj wytrenowaną sieć do formatu onnx a następnie zademonstruj jej działanie projekcie Unity. 

2. [5 punktów] Wytrenuj sieć neuronową segmentującą obrazy kotów. Link do zbioru treningowego i walidacyjnego: [link](https://aghedupl-my.sharepoint.com/personal/thachaj_agh_edu_pl/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fthachaj%5Fagh%5Fedu%5Fpl%2FDocuments%2FMGU%5Flab%2Fdane%5Fdo%5Fsegmentacji%2Ezip&parent=%2Fpersonal%2Fthachaj%5Fagh%5Fedu%5Fpl%2FDocuments%2FMGU%5Flab&ga=1) [link zapasowy](https://www.dropbox.com/scl/fi/nowclt6obl10q4h28ajj5/dane_do_segmentacji.zip?rlkey=jq14ixql1wxdgv0uvubp9y6jy&st=jjmdz8k2&dl=0). Określ skuteczność modelu. Wyeksportuj wytrenowaną sieć do formatu onnx a następnie zademonstruj jej działanie projekcie Unity. 

Pod adresem [link](https://home.agh.edu.pl/~thachaj/mgu/python/TensorflowKerasNoGPU/requirements.txt) znajdziesz plik requirements.txt zawierający zestaw pakietów Python które używałem na wykładzie podczas treningu sieci.

## Zadanie dodatkowe!

Jeżeli wykonasz powyższe zadania spróbuj zaimplementować w Unity aplikację, która przy pomocy sieci wytrenowanej na zbiorze ImageNet będzie dokonywała klasyfikacji obrazu pochodzącego z kamery umieszczonej na scenie Unity. Przetestuj działania aplikacji na kilku wirtualnych scenach, na których będą znajdować się modele obiektów, które znajdują się pośród klas istniejących w zbiorze  ImageNet [link](https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a).
Jeżeli zrobisz to zadanie otrzymujesz dodatkową ocenę 5.0.

Powodzenia (◟ᅇ)◜
