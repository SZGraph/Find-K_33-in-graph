# Функция поиска полного двудольного подграфа K_{3,3} 
На входе граф - объект networkx\
На выходе:\
list_k3 - список вершин полных двудольных подграфов, изоморфных К_{3,3} графа G.\
Функция полезна для приведения графа к планарному виду. Для этого нужно удалить любую вершину из каждого найденного подграфа.\
Отдельно потребуется побороться с кликами K_5 в графе, например с помощью [find_cliques](https://networkx.org/documentation/stable/reference/algorithms/generated/networkx.algorithms.clique.find_cliques.html).\
\
В файле .ipynb приведен пример поиска К_{3,3} в модели вэб-графа Бакли-Остгуса при 𝑛=2000,𝑚=3,𝑎=1/3. В данном примере клика будет трактоваться как 3 возможно несвязанных сайта, ссылающиеся на 3 иные возможно несвязанные сайта.

* Блокнот [.ipynb: ](https://drive.google.com/file/d/17Qust07Ionef8HmN_OSuFglS5awu3mbJ/view?usp=sharing)
