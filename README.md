Nowoczesne Technologie Przetwarzania Danych


Lab 10


Temat: Analizy danych w Spark SQL


Dominika Liszkiewicz


Zadanie 1


<img width="671" height="524" alt="image (38)" src="https://github.com/user-attachments/assets/2c757104-ba7b-4528-aa77-951e7e4bc6d2" />



Zadanie 2 


Wyniki zapytania


<img width="718" height="322" alt="image (39)" src="https://github.com/user-attachments/assets/7a1e77e4-1beb-4314-8e6b-b18b7f0953f9" />


Zadanie 3 


W zapytaniu Spark połączył dane o zakupach z danymi o klientach za pomocą id klienta. Odrzucił zakupy poniżej 100 złotych, posegregował transakcje według rodzaju produktu i obliczył podstawowe statystyki dla każdej grupy produktów.


<img width="1137" height="266" alt="image (40)" src="https://github.com/user-attachments/assets/f4535e4a-bc9a-479b-8065-c4620e8a6bc5" />



Najwięcej sprzedanych zostało laptopów i telefonów. Cene laptopa była zdecydowanie najwyższa, a cena monitora najniższa. 


Wnioski:


- w zadaniu 2 Spark sam otworzył pliki i zorientował się gdzie są nagłówki kolumn oraz dobrze określił typy danych



- format parquet jest binarny i kolumnowy, zapisuje skompresowane dane i przechowuje też metadane, dzięki temu Spark może odczytać tylko te dane, które są mu potrzebne


- używanie widoków tymczasowych pozwala pisać czysty kod SQL
