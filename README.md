# Remote-Sensing
Практика по алгоритмам классификации спутниковых снимков. Рассмотрены следующие модели.

1. Spectral Angle Mapper

2. Spectral Information Divergence

3. Модели, разработанные по результатам [2018 IEEE GRSS Data Fusion Challenge](https://hyperspectral.ee.uh.edu/?page_id=1075)

Форк репозитория со всеми моделями:
https://github.com/sergbelom/DeepHyperX

В работе рассмотрено две модели:

* baseline neural network (4 fully connected layers with dropout)
* 3D CNN ([3-D Deep Learning Approach for Remote Sensing Image Classification, Hamida et al., TGRS 2018](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8344565))

  [ссылка на открытую статью (researchgate)](https://www.researchgate.net/publication/325816861_Three_dimensional_Deep_Learning_approach_for_remote_sensing_image_classification)


Модели можно запустить с помощью docker контейнера
https://hub.docker.com/repository/docker/sergbelom/deephyperx
