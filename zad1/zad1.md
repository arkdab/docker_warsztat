## 1. Pobrać program app.py
## 2. Stworzyć Docker file w którym można uruchomić program w python 3
## 3. Stworzyć obraz ze stworzonego DockerFile



## 4. Stworzyć kontener ze stworzonego obrazu i uruchomić aplikację webową na porcie: 1234  

UWAGA ta komenda jest niezbędna do uruchomienia aplikacji webowej pythonie:
dodaj ją do dockerfile:
RUN pip install --trusted-host pypi.python.org -r requirements.txt

plik requirements.txt będzie potrzebny - jest w katalogu z zad1



Wynik uruchom przegladarke i wpisz http://localhost:1234