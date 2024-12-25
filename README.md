Rivalz CLI Kurulum


#Sırasıyla#      

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
source ~/.bashrc

nvm install 20.0.0
nvm use 20.0.0

#Ardından Screen Oluşturuyoruz#
screen -S rivalz

#CLI Yükleme Komutu#
npm i -g rivalz-node-cli

#Rivalz'ı Çalıştırmak İçin Komutu Girelim (EVM adresimizi ve ne kadar bir alan kullanmak istediğimizi belirleyelim)#
rivalz run
