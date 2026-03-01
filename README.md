# Sztuczna Inteligencja 25/26

Repozytorium przedmiotu „Sztuczna Inteligencja” w roku akademickim 25/26 na Wydziale Elektrotechniki i Informatyki PRz. 

## Zasady 
Obecność na laboratorium:
- jest obowiązkowa, dopuszcza się jedną nieusprawiedliwioną nieobecność,
- nieobecność nie zwalnia z oddania rozwiązanego ćwiczenia,
- nieobecność nieusprawiedliwiona równa się z otrzymaniem 0 punktów za wejściówkę,
- nieobecność usprawiedliwić można tylko na najbliższych zajęciach, na ktorych student jest obecny, może też wtedy podejść do poprzedniej wejściówki.

W trakcie każdych zajęć studenci otrzymują do wypełnienia notebooka z ćwiczeniami. Na początku semestru należy założyć **prywatne** (!) repozytorium na GitHubie przeznaczone na rozwiązane notebooki oraz dać dostęp do repozytorium prowadzącemu ćwiczenia. Notebook powinien być wypełniony do kolejnych ćwiczeń i będzie on stanowił sprawozdanie z laboratorium. Notebooki nie są oceniane, jednak powinny być wypełnione co najmniej w 60%. Niedostarczenie notebooków do kolokwium zaliczeniowego będzie stanowiło brak dopuszczenia do niego. 

Na ocenę z ćwiczeń składać będą się punkty z kolokwium oraz z wejściówek zgodnie z ustaleniami na pierwszych zajęciach.

Niedozwolone jest:
1. Udostępnianie innym studentom rozwiązania zadania w formie szczegółowego opisu algorytmu bądź kodu.
2. Korzystanie z pomocy innych bądź narzędzi podczas wejściówek lub kolokwium.
3. Korzystanie podczas zajęć z dużych modeli językowych w celu uzyskania rozwiązania. 

## Środowisko 
### Colaboratory (zalecane)
Należy wrzucić folder z repozyrtorium na swojego Google Drive, następnie otworzyć ten plik i z dostępnych aplikacji wybrać Colaboratory.
### Conda (alternatywnie)
Należy ściągnąć oraz zainstalować minicondę: https://conda.io/en/latest/miniconda.html (nie trzeba jeśli zainstalowana Anaconda).

Stworzyć środowisko razem z podstawowymi bibliotekami: `conda create --name ai26 python=3.11 numpy=2.4.2 scipy=1.17 matplotlib=3.10.8 scikit-learn=1.8.0 jupyter`

Aktywować środowisko i w celu korzystania z jupyter użyć: `jupyter lab`
Wraz z kolejnymi laboratroiami będzie istania konieczność doinstalowywania kolejnych pakietów (jak np. pytorch). 


