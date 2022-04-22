# Jogo2-IniciandoEmJavaScript-Aula-3
Aprendendo listas e repetindo comandos

Nessa aula aprendemos:

* Diminuir a quantidade de variáveis utilizando listas
* Removemos os códigos duplicados, utilizando laços de repetição e contadores em cada iteração;
* Extraímos a verificação que identifica se o carro passou toda a tela para uma nova função chamada passouTodaATela().

## Instruções:

### Melhorando o código com listas

* Para não precisarmos escrever uma variavel para cada yCarro, podemos criar uma lista
* Então chamamos uma lista de "let yCarros = [posição de cada carrinho]"
* Depois substituimos aonde estavamos usando a variavel por yCarros[0-n] (o número que vai entre conchetes é o número de da posição de cada termo na lista, sendo o primeiro sempre o número 0)
* Agora só fazer o mesmo para o xCarros e velocidadeCarros;
* Não esqueça de substituir as variaveis nas funções


### Melhorar o código com Repetições (loops)

* Para simplificar ainda mais nosso código, podemos deixar o carregamento da imagem em loop com o compando for
* Então, primeiramente vamos criar uma lista com as imagens, la no arquivo imagens.js e padronizar nosso código.
* function mostrarCarro() {
  image(imagensCarros[0], xCarros[0], yCarros[0], 50, 40);
  image(imagensCarros[1], xCarros[1], yCarros[1], 50, 40);
  image(imagensCarros[2], xCarros[2], yCarros[2], 50, 40);
* Assim, podemos criar um comando for ()[], criar um indice, e mandar o programa fazer a repetição para o tamanho da lista
* primeiramente criamos uma variavel "let i = 0" para começar do primeiro elemento
* depois damos a condição de i ser menor do que o tamanho da lista "i < imagensCarros.length"
* depois somamos 1 ao indice e o programa fará por todos os parametros;
* Agora é só fazer o mesmo para a função de movimentar os carros e para a função de fazer eles voltarem para a posição inicial
