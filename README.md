# ML-Audio-Music-Genre-Classification
# ML Audio: Классификация музыкальных жанров.
Задача: определить музыкальный жанр, анализируя аудио. 

Датасет: https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification 
Датасет представляет собой аудиофайлы, изображения мел-спектрограмм, 2 таблицы (для 3 сек. и 30 сек.) со ссылками на аудио-файлы и рассчитанными характеристиками звука.  
 
Данные загружены, характеристики звука в таблице исследованы, построены графические отображения ряда характеристик.
Построена модель Keras (MPL).
Использованы данные таблицы с разбивкой по 3 сек., обучена и протестирована модель. Выведено значение accuracy для модели и для каждого жанра.
Затем данные таблицы дополнены значениями 64-х коэффициентов PCEN (per-channel energy normalization), модель повторно обучена и протестирована. 

Использованы библиотеки librosa, Кeras.
