# galaxy_rotation_curve
Primeiro teste para implementação de um modelo para estimar a distribuiçao de massa na galáxia.

Foi realizado um estudo simples no qual foi considerada uma galáxia bidimensional somente com as coordenadas $(r, \theta)$ com densidade de massa variável dependendo somente da componente radial. A galáxia foi dividida em anéis concentricos cuja distribuição de massa dava origem a uma força em um ponto $x_{i}$. 

Deste modo, foi possível calcular a velocidade de rotação em um ponto $x_{i}$ devido à massa do disco e do bojo, que foi estimado pelo perfil de densidade de Hernquist.

Os resultados estão, como esperado, aquém do real (visto pelos dados experimentais utilizados por Clemens, em 1985), no entanto nesta primeira estimativa rústica não foi levado em consideração um eventual Halo de matéria escura.

Os resultados obtidos podem ser vistos abaixo:

![plot_curva_rotacao](https://github.com/gabrieltxg/galaxy_rotation_curve/blob/main/teste_curva_rotacao_aneis.png)
