# install_chrome


단축키 Ctrl + Alt + T를 눌러 터미널창을 띄운 뒤

wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -

sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'

sudo apt-get update

sudo apt-get install google-chrome-stable

ls /etc/apt/sources.list.d/google*

sudo rm -rf /etc/apt/sources.list.d/google.list

크롬설치 icon check
