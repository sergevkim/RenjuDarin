# DarinKim
Deep and reinforced intelligence net Korean inquisitive mind! 
I believe my creation will play better than me

Есть несколько ключевых файлов:

0) night_model.hdf5 - модель с обученными весами
1) preparation.ipynb - это для подготовки даты из игр профессионалов (нужно только для обучения модели)
2) nn.ipynb - обучение
3) user_interface.ipynb - красивая доска для игры вдвоем с подсказками модели, для ее запуска необходима night_model.hdf5 и папка images
4) darinkim2.py - мой агент

![Screenshot](/images/BOARD_EXAMPLE.png)

Чтобы поиграть с ботом, необходимо запустить ноутбук user_interface.ipynb. После каждого хода в кнопке под словом "Prediction" будет публиковаться рекомендуемый ботом ход. Пояснительная записка - explanation_note.pdf. 


Версии библиотек, при которых все точно работает:
tensorflow 1.12.0
keras 2.2.4
tkinter 8.6
