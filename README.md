# Touchpad Lenovo S145

Em alguns modelos de notebook da Lenovo o touchpad não funcionam em distribuições Linux, por exemplo, no Ubuntu 20.04 LTS, que é o meu caso. Siga os passos abaixo para corrigir o problema.  

1. Usando *sudo* e seu editor de texto favorito copie o texto do arquivo *TouchpadFile* para dentro de */etc/default/grub*.
2. Rode o comando: `sudo update-grub`
3. Reinicie o notebook.
