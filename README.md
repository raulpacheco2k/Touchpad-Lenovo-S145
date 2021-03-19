# Touchpad Lenovo S145

Em alguns modelos de notebook da Lenovo o touchpad não funcionam em distribuições Linux, por exemplo, no Ubuntu 20.04 LTS, que é o meu caso. Siga os passos abaixo para corrigir o problema.  

1. Usando *sudo* e seu editor de texto favorito copie o texto do arquivo [*TouchpadFile*](https://github.com/raulpacheco2k/Touchpad-Lenovo-S145-Elan/blob/main/TouchpadFile), para dentro de */etc/default/grub*.
2. Se já tenha uma linha a com variavel GRUB_CMDLINE_LINUX_DEFAULT no arquivo */etc/default/grub*, apaguea e coloque a linha em seu lugar.
3. Rode o comando: `sudo update-grub`
4. Reinicie o notebook.
