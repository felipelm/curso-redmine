# Instalação

![](https://rvm.io/images/rvm-logo-all-happy.png)

Para instalar o Ruby no Linux **(Usem LINUX)**, vamos utilizar um gerenciador de versão do Ruby para conseguirmos ter mais de uma versão rodando na mesma máquina.

Os dois gerenciadores mais famosos são o rbenv e o rvm. Para esse curso vamos utilizar o rvm.

<sub><sup>Escolha baseada em gosto pessoal, se quiserem se aventurar no rbenv ele também é muito bom.</sup></sub>

```sh
$ apt-get update
$ apt-get install -y subversion git telnet
$ apt-get install -y libmysqlclient-dev freetds-dev imagemagick libmagickcore-dev libmagickwand-dev libcurl4-openssl-dev apache2-threaded-dev libapr1-dev libaprutil1-dev curl

$ gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3

$ \curl -sSL https://get.rvm.io | bash -s stable

$ rvm requirements
$ rvm install 2.2
$ rvm use 2.2 --default
```