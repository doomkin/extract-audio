# Извлечение аудио

# Установка

1. Установите необходимые команды
```bash
sudo apt install ffmpeg rename
```

2. Клонируйте этот репозиторий
```bash
git clone https://github.com/doomkin/extract-audio.git
```

3. Дайте права на выполнение файла `extract-audio`
```bash
cd extract-audio
chmod +x extract-audio
```

# Использование

1. Скопируйте файл `extract-audio` в каталог с видео в формате **mp4**.
2. Запустите `extract-audio`
```bash
./extract-audio
```

# Результат

В каталоге с видео появится каталог `audio` с файлами **mp3**. Пропишите теги mp3 в программе `easytag` для удобного прослушивания в плеере.
