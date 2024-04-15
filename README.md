# recursive_function_no_recurency
#
Funkcja sum_from_string przyjmuje ciąg znaków list_str jako argument.

Inicjuje pustą listę numbers, która będzie przechowywać liczby znalezione w ciągu.

Następnie iteruje przez każdy znak w ciągu list_str za pomocą pętli for.

Dla każdego znaku sprawdza, czy jest cyfrą za pomocą metody isdigit(). Jeśli tak, konwertuje ten znak na liczbę całkowitą i dodaje do listy numbers.

Jeśli znak jest myślnikiem -, sprawdza kolejny znak za pomocą funkcji next(list_str) i jeśli jest to również cyfra, łączy je w jedną liczbę i dodaje do listy numbers.

Po zakończeniu iteracji oblicza sumę wszystkich liczb w liście numbers za pomocą funkcji sum() i zwraca tę sumę.git status
