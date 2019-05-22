# ZMS2019
Symulacja kolejkowa 

Market Piotr i Paweł ma kasy, do któych co X (rozkład) sekund przychodzą klienci (jak uwzględnić godziny szczytu?)
Jeśli przed klientem do kasy stoi więcej niż 5 klient otrzymuje on 10% zwrot kwoty zakupów. Jeśli klient stoi w kasie
za długo może dojśc do zjawiska zrezygnowania z przyszłych zakupów (jakaś dystrybuanta) [do implemetacji lub odrzucenia]. Wartość zakupu ma pewien rozkład, a w wypadku churnu tracimy klienta na cały horyzont symulacji, gdzie średnia liczba zakupów w miesiącu i ich wartość
również będzie losowana wg rozkładu

Funkcje:
Symulacja kolejnych przychodzących klientów - do n kas, do których jest wspólna kolejka

Czas obsługi - skorelowany z wielkością zakupów
Losowanie wartości zakupu
Losowanie odejścia (churn) i parametrów klienta???
Wyznaczanie zwrotu dla klientów, których numer w kolejce jest większy lub równy 6 (w momencie kiedy do niej przychodzi)

Funkcja odpalająca symulację itd. itp.

'''
