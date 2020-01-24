# NFLDataProj
Data analysis project

Projekt zawiera próbę rozwiązania problemu regresji. Przedstawione ono zostało jako przewidywanie końcowej pozycji gracza z piłką po zagrywce. 
Każda zagrywka jest opisana przez szereg danych związanych z meczem (m.in. typ stadionu, nawierzchni, pogoda), z sama zagrywką (m.in. która ćwiartka gry, wynik do tej pory, siła i kierunek wiatru) oraz  z poszczególnymi graczami (położenie na boisku, wektor prędkości, przyspieszenie, rola w drużynie).

W naszym modelu skupiliśmy się głównie na danych opisujących indywidualnych graczy i odrzuciliśmy większość danych ogólnie związanych z całym meczem (jak nazwa college'u, drużyny, stadionu), nie uwzględniliśmy też wektora wiatru, bo nie był podawany względem położenia (orientacji) stadionu.

Z danych kategorialnych zachowaliśmy rolę gracza w drużynie , ponieważ różne rozkłady yardów dla poszczególnych ról sugerowały jakiś związek, oraz formacje drużyny atakującej (będącej w posiadaniu piłki), z tego samego powodu.

Nauczyliśmy podstawowe modele regresji: Ridge, Decision Tree, Random Forest, SVR, XGBoost, Ada Boost.
Spośród nich najlepiej nauczył się Random Forest a najgorzej Ada Boost. Jednak generalnie generalnie różnice żadnemu z modeli nie udało się dobrze uchwycić tak przedstawianych danych i różnice między nimi nie były duże.
