# google_drive_downloader
#Скрипт для загрузки файлов из Google Drive из консоли.

#Скачиваем скрипт и делаем его исполняемым:
sudo wget -O /usr/sbin/gddl 'https://github.com/yarapolkez/google_drive_downloader/blob/main/gddl'
sudo chmod +x /usr/sbin/gddl

#Варианты использования:
gdrivedl https://drive.google.com/open?id=1sNhrr2u6n48vb5xuOe8P9pTayojQoOc_
gdrivedl https://drive.google.com/file/d/1sNhrr2u6n48vb5xuOe8P9pTayojQoOc_/view?usp=sharing
gdrivedl 1sNhrr2u6n48vb5xuOe8P9pTayojQoOc_
gdrivedl https://drive.google.com/open?id=1sNhrr2u6n48vb5xuOe8P9pTayojQoOc_ /tmp/my_file.rar
