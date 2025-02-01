Данный проект представляет собой приложение, которое использует вебкамеру для захвата видеопотока и выполняет распознавание лиц в реальном времени.
## Описание
Программа позволяет подключить вебкамеру, отображать видеопоток и автоматически распознавать лица на изображении с использованием алгоритмов компьютерного зрения. 
Скриншоты с распознанными лицами можно просматривать в панели справа и сохранять на диск.
## Установка

1. Скачайте или клонируйте репозиторий:
   git clone https://github.com/Dwanlisid046/FaceWebcamDetection.git
2. Необходимые пакет из Nuget 
  Install-Package Emgu.CV
## Использование
1)Запустите приложение.
2)Выберите доступную камеру для захвата видео из выпадающего списка.
3)Нажмите кнопку "Смотреть", чтобы начать захват видеопотока с камеры.
4)Когда лицо будет найдено, оно будет обведенно красным прямоугольником, и будет сделан скриншот.
5)Скриншоты с распознанными лицами будут отображаться в панели справа.
