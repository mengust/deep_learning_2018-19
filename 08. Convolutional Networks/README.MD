
# Восьмое занятие
Приветствуем Вас на **восьмом** занятии нашего курса. Сегодня мы перейдем к изучению еще одного типа нейронных сетей --- сверточных. Именно развитие таких сетей произвело революцию в computer vision, позволив компьютеру обгонять человека в задачах распознавания объектов. 

### План занятия
#### 1. Лекция
Сверточные сети так называются, потому что в них используются сверточные слои. Эти слои проводят над картинками операцию, которая в математике называется свертка, но такое объяснение слишком сложно  и не дает интуитивного понимания работы сверточных слоев. Есть намного более простое объяснение, основывающееся на том, что свертка позволяет узнавать на картинке некоторые паттерны. Чтобы узнать обо всем этом Вы можете посмотреть [**запись**](https://www.youtube.com/watch?v=Xul1DS08hSA) лекции, слайды с лекции --- [**conv_nets.pdf**](./conv_nets.pdf). Также в поисковике Вы можете найти много других объяснений, если лекции оказалось недостаточно

#### 2. Операция свертки и пулинг
Дополнительно объяснение того, как работает свертка, вы можете найти в тетрадке [**[seminar]convolution_pooling.ipynb**](./[seminar]convolution_pooling.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/16hH-O-mzYyyD0F4QfGQyGjLzEvfdSy9K). Это объяснение поможет вам понять, как можно реализовать свертку в Python. Также в тетради рассматривается еще один важный слой - слой пулинга, который позволяет сжимать информацию в картинке. В освоении материала Вам поможет [**запись**](https://www.youtube.com/watch?v=ZxTOUTD0QK8) семинара.

#### 3. Сверточные нейросети на PyTorch
Теперь пришло время использовать наши теоретические знания и создать свою сверточную нейросеть на PyTorch для классификации cifar10. Чтобы понять, как это делать просмотрите объяснения и сделайте задачи в ноутбуке [**[seminar]convnet_pytorch.ipynb**](./[seminar]convnet_pytorch.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1OqQ4r0lo-Mm-6JBmNu9wsD_MfLbWwg7s), с выполнением заданий Вам поможет запись семинара, ссылка на которую есть выше. После выполнения вы можете заметить, насколько лучше сверточные нейросети подходят для классификации картинок, чем просто полносвязные.
