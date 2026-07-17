# Face Recognition Project

Учебный проект по задаче распознавания лиц. Задание в [блокноте](https://drive.google.com/file/d/1qMN2tIEkG36KaNTFTYJjpDk7_Ws1lU9B/view?usp=sharing).

1_1_dataset.ipynb - в блокноте создается датасет для обучения модели предсказания ключевых точек

1_2_hourglass.ipynb - в блокноте обучается модель предсказания ключевых точек (этот файл не открывается в гитхабе, поэтому вот [блокнот на гугл диске](https://colab.research.google.com/drive/1Ja2h3yYXow4gYu9LBD-GorkIkivhCbt5?usp=sharing))

1_3_alignment.ipynb - в блокноте создается датасет для обучения модели распознавания лиц

2_1_CE.ipynb - в блокноте обучается модель распознавания лиц с помощью CE loss

2_2_ArcFace.ipynb - в блокноте обучается модель распознавания лиц с помощью ArcFace loss

2_3_ArcFace.ipynb - в блокноте дообучается предыдущая модель еще на 10 эпох

3_pipeline.ipynb - в блокноте собирается пайплайн распознавания лиц

4_1_dataset.ipynb - в блокноте создается датасет для оценки моделей распознавания лиц

4_2_Identification_Rate_Metric.ipynb - в блокноте оцениваются обученные модели

data/ - папка, содержащая csv-файлы со списками названий файлов из датасета CelebA

data/cropped/ - датасет для обучения модели предсказания ключевых точек (картинки в [архиве](https://drive.google.com/file/d/1iKgflhMnXPJ_8TZLMHe8HipGFQXoLbDD/view?usp=sharing))

data/aligned/ - датасет для обучения моделей распознавания лиц (картинки в [архиве](https://drive.google.com/file/d/1rX8KmTx0KZjz_WsXkEq0Jq4dnPIoHCb3/view?usp=sharing))

data/metric/ - датасет для оценки обученных моделей (картинки в [архиве](https://drive.google.com/file/d/1j4TTSaXq6F3JlkrpBYlVGRjVWsDY_Q9_/view?usp=sharing))

samples/ - картинки, которые использовались в задании 3

output/ - вырезанные и выровненные лица из картинок задания 3, и информация о прямоугольниках лиц, ключевые точки и эмбеддинги

веса моделей в [архиве](https://drive.google.com/file/d/16VXB3FIWI85rUkxLFJtaerJou5eF5mo6/view?usp=sharing)
