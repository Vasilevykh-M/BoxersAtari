# BoxersAtari
### Данный репозиторий содержит модель машинного обучения, а именно обучения с подкреплением, для игра на Atari Boxing
При построении моделей было выявленно несколько сложностей
#### 1. Боксер не подходит к противнику
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Results/1.gif)
#### Ввести награду за приближение к противнику
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Results/2.gif)
#### 2. Боксер смещается лишь по одной оси
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Results/2.gif)
#### Наказывать за долгий простой большим штрафом
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Results/3.gif)
#### 3. Боксер зажимает противника в его же углу и не бьет
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Results/3.gif)
#### Ввести радиус нахождение в котором дается награда
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Results/4.gif)

### Было реализовано несколько моделей, но приемлемый результат давала, использующая сверточную сеть (Google DeepMind)
#### "Слепой агент 1"
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Models/1.png)

В ней заложенна полносвязная нейронная сеть принимающая на вход положение первого и второго боскера (координаты рук и головы, рассчитаные исходя из цвета боскера)
#### "Слепой агент 2"
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Models/2.png)

В ней заложенна полносвязная нейронная сеть принимающая на вход положение первого и второго боскера (координаты рук и головы, рассчитаные исходя из цвета боскера)
#### Модель использующая сверточную сеть (Google DeepMind)
![](https://github.com/Vasilevykh-M/BoxersAtari/blob/main/Models/3.png)

В этом модели используются сверточные сети
