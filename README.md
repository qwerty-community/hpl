# hpl
Hack Password in Linux

RU:
отказ от ответственности:
Этот репозиторий предназначен для сброса пароля в ВАШЕЙ системе и для тестирования безопасности. Ни в коем случае не используйте этот инструмент в корыстных целях. Автор отказывается нести ответственность за ваши действия и не призывает причинять кому либо вред. 

HPL (Hack Password in Linux) - инструмент для сброса пароля в системах Linux. Сброс выполняется путем замены исходного хэша в файле "etc/shadow" на свой собственный. После того, как программа выполнит свою работу, вы сможете войти в систему с новым паролем. Пароль: qwerty 

Репозиторий защищён авторским правом! Если вы хотите его свободно редактировать для публикации, свяжитесь с нами. 

Вы можете посмотреть видеоурок на YouTube о том, как использовать этот инструмент:
https://youtu.be/WYGnSssWlRs

Как запустить:
1. Запуститесь с live-дистрибутива linux 

2. Скачайте репозиторий:
git clone https://github.com/qwerty-community/hpl 

3. Перейдите в папку:
cd hpl 

4. Запустите инструмент:
python3 hpl.py 

Протестировано на kali linux


Примечание:
Инструмент создаст резервную копию файла с хэшами. Найти резервную копию вы сможете в той папке, где и запускали инструмент.



EN: 

disclaimer of liability:
This storage is designed for password reset on YOUR system and for security testing. In no case do not use this tool for selfish purposes. The author refuses to be responsible for your actions and does not encourage anyone to cause harm. 

HPL (Hack Password in Linux) - a tool for password reset in Linux systems. The reset is performed by replacing the original hash in the "etc/shadow" file with its own. After the program completes its work, you will be able to log in with a new password. Password: qwerty 

The repository is copyrighted! If you want to edit it freely for publication, please contact us. 

You can watch a video tutorial on YouTube on how to use this tool:
https://youtu.be/WYGnSssWlRs

how to launch:
1. Start with a live linux distribution 

2. Download the repository:
git clone https://github.com/qwerty-community/hpl 

3. Go to the folder:
cd hpl 

4. Run the tool:
sudo python3 hpl.py 

tested on kali linux


note:
just in case, the tool will create a backup copy of the file with hashes. You can find the backup in the folder from which you launched the tool.
