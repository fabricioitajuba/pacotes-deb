# Exemplo de pacotes .deb

- A pasta atualiza/ contém o conteúdo do pacote.

- O pacote atualiza.0.1.deb foi criado através do seguinte comando:

$ dpkg-deb -b atualiza/ atualiza.0.1.deb

- para instalar:

$ sudo dpkg -i atualiza.0.1.deb

- para desinstalar:

$ sudo apt remove atualiza

- Para aprender como criar um pacote, consulte o arquivo "Como criar pacotes deb.txt" no repositório "Linux-Help".

