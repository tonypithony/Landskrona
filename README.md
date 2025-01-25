![](https://raw.githubusercontent.com/tonypithony/Landskrona/refs/heads/main/cron_ubuntu.jpg)

The --host option to flask run, or the host parameter to app.run(), controls what address the development server listens to. By default it runs on localhost, change it to flask run --host=0.0.0.0 (or app.run(host="0.0.0.0")) to run on all your machine's IP addresses.  

0.0.0.0 is a special value that you can't use in the browser directly, you'll need to navigate to the actual IP address of the machine on the network. You may also need to adjust your firewall to allow external access to the port. [1](https://stackoverflow.com/questions/7023052/configure-flask-dev-server-to-be-visible-across-the-network)

![](https://raw.githubusercontent.com/tonypithony/Landskrona/refs/heads/main/Rotterdam.Ahoy.jpg)

```bash
$> sudo nano /etc/crontab
@reboot root /home/van_rossum/mount_terradisk_pop_os.sh

$> crontab -e
@reboot /home/van_rossum/webguillm.sh
```

## Sources

* [cron](https://help.ubuntu.ru/wiki/cron)
* [Cron: что это такое и как его правильно использовать](https://timeweb.com/ru/community/articles/chto-takoe-cron)

# Bonus №1: Удаленный доступ для всех

![](https://raw.githubusercontent.com/tonypithony/Landskrona/refs/heads/main/844c2b846ea1ac64f9961fb20c4c2934.jpg)

## Sources

* [NoMachine — программа, бесплатная для всех](https://www.nomachine.com/ru)
* [Как установить NoMachine на Ubuntu, Debian и LinuxMint (альтернатива TeamViewer)](https://linux16.ru/articles/kak-ustanovit-nomachine-na-ubuntu-debian-i-linuxmint-alternativa-teamviewer.html)


# Bonus №2: [Jan is an open source ChatGPT-alternative that runs 100% offline.](https://jan.ai/)

![](https://raw.githubusercontent.com/tonypithony/Landskrona/refs/heads/main/Capture.PNG)

![](https://raw.githubusercontent.com/tonypithony/Landskrona/refs/heads/main/file_830_17_picdumps_nikita_klaestrup_sexy_danish_student_politician.webp)
