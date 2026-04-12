**[← Powrót do strony głównej](/)** | **[Powrót do listy projektów](/projekty)**

# Machine-Learining-Exercises
Repozytorium zawiera zadania dotyczące regresji liniowej, tworzenia prostego modelu gęstej sieci neuronowej, uczenia modeli sieci splotowych i rekurencyjnych.

## Zadanie 1

* **Temat**: Regresja liniowa, grzbietowa, gradient descent.
  * Napisanie w Pythonie funkcji do dopasowania modelu regresji liniowej, estymacja współczynników modelu za pomocą metody najmniejszych kwadratów. Stworzenia predykcji zmiennej objaśnianej na podstawie zmiennych objaśniających.

  * Napisanie w Pythonie funkcji do dopasowania modelu regresji grzbietowej, minimalizacja funkcji kosztu metodą iteracyjną. Stworzenia predykcji zmiennej objaśnianej na podstawie zmiennych objaśniających.

## Zadanie 2

* **Temat**: Gęsta sieć neuronowa (DNN).
  * Ręczna implementacja sieci neuronowej z wieloma warstwami.

  * Wykorzystanie algorytmu forward propagation oraz back propagation w celu uczenia modelu sieci neuronowej.

  * Dobór wag początkowych oraz funkcji aktywacji.

  * Analiza modelu na podstawie zbioru danych MNIST - baza z ręcznie pisanymi cyframi.. Wykorzystano pliki `mnist.pkl.gz` oraz `mnist_loader.py` ([link do repozytorium](https://github.com/MichalDanielDobrzanski/DeepLearningPython))

  * Porównanie modeli różniących się, wielkością warstw, funkcją aktywacji (ReLU, sigmoid).

## Zadanie 3

* **Temat**: Sieci splotowe (CNN).
  * Tworzenie modeli za pomocą bibliotek `tensorflow` oraz `keras`

  * Podział danych `CIFAR-10` na zbiór uczący, walidacyjny oraz testowy.
  
  * Uczenie stworzonych modeli na podstawie zbioru danych `CIFAR-10`.

  * Tworzenie wizualizacji wyników za pomocą bibliotek `matplotlib` oraz `seaborn`.

  * Modyfikacja hiperparametrów, m.in. liczba i rozmiar filtrów, stride, padding, funkcje aktywacji.
  
  * Stosowanie metod takich jak dropout, batch normalization, maxpooling, w celu poprawienia dokładności klasyfikacji danych przez model.