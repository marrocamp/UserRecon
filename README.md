# UserRecon v1.0
# Author: @marrocamp
# https://github.com/marrocamp/userrecon

Encontre nomes de usuário em mais de 75 redes sociais
Isso é útil se você estiver executando uma investigação para determinar o uso do mesmo nome de usuário em diferentes redes sociais.

![userrecon](https://user-images.githubusercontent.com/15244775/67907704-9dd1a700-fb57-11e9-9ede-2de5b9b360c4.png)

Instalação:
01 Passo
Realize o download e acesso o diretório UserRecon

root@kali:/# git clone https://github.com/marrocamp/userrecon.git
root@kali:/# cd userrecon
root@kali:/userrecon# ls -l

02 Passo
Atribuir a permissão de execução no script userrecon.sh em seguida executá-lo.

root@kali:/userrecon# chmod +x userrecon.sh
root@kali:/userrecon# ./userrecon.sh

03 Passo
Informe o nome do usuário no qual deseja pesquisar
exemplo: marrocamp

04 Passo
Um arquivo com o nome do usuário é gerado contendo a relação de todos os cadastros encontrados com o nome: (ex.)
marrocamp
root@kali:/userrecon# cat marrocamp.txt
