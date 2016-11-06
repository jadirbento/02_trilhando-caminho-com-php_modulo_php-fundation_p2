# CURSO - TRILHANDO CAMINHO COM PHP

Este curso é ministrado por Wesley Willians da [School Of Net](https://www.schoolofnet.com/).

> O curso é composto por 11 módulos.
> Dividido em várias fazes, com testes práticos corrigidos pelo professor.

# Anotações
### Comandos de terminal.

`$ php -v` Mostra a versão do PHP. Mas, é mais do que isso, você verifica se o PHP esta rodando corretamente.

`$ php -a` Inicializar o shell
````sh
Exemplo: 
php > $x = 5;
php > $y = 5;
php > $x + $y;
10
````

`$ php -r` Executa o php ***SEM CRIAR ARQUIVOS, SEM ESTAR SHELL*** sem tags de abertura e fechamento (<?php >). 

Exp:`$ php -r "echo 'teste';"`

`$ php -m` Lista os módulos que estão instalados.

`$ php -m | grep nome-do-modulo` Verifica um módulo específico.

`$ php -i` Traz o phpinfo()

### PHP Built-in Server
Levantar o servidor embutido do PHP.

`$ php -S localhost:8085` Levanta o servidor na porta indicada.

##### Setar o document root da aplicação
`$ php -S localhost:8085 -t public_html/` Ele informa ao php que o ***document root*** esta dentro de public_html

# Sobre o Vagrant e PuPHPet
Uma ótima opção para quem trabalha em equipe e quer garantir que todos tenham o mesmo ambiente de desenvolvimento é a utilização o Vagrant.

***===================== Anotações sobre PHP ======================***

### PuPHPet
Recentemente gravei um vídeo sobre PuPHPet em meu canal do youtube. [Acesse clicando aqui.](https://www.youtube.com/watch?v=nK6NFDiOqjE) (O screencast está com um crop terrível, mas acho que vocês conseguem entender a idéia).

### Qual a diferença entre require e inlcude?
 Quando utilizamos require, e o arquivo não for encontrado o PHP retornará um Fatal error, já o include apenas um warning e a aplicação continuará rodando.
 
 
 
 