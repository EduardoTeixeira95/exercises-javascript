# exercises-javascript
Neste campo irei adicionar todos os meus exercícos, aprendizados e rotina diaria de estudos em minha carreira pessoal e profissional

Lista_1

aula_1: Criar uma página HTML que contenha um formulário com os campos nome,  pontos, nota, universidade, empresas, avatars, horários. Podem utilizar o  elemento input type text do form HTML para esses campos. Além disso criem um  botão type submit.

aula_2 e 3: Crie uma função Javascript que permita validar o formulário criado no  exercício 01 quanto a obrigatoriedade dos campos para submit do form no botão  submit. 

Transformar os campos “elementos“ da página criada no exercício 01, em  tipos de campos apropriados para o domínio de informação neles contidos.  Ex.: o campo “avatars” ao invés de utilizar um “input text” poderia utilizar um  “select” visto que ele pode conter uma lista multivalorada de itens para seleção, o  famoso “combobox”.

aula_4: Utilizando o objeto Javascript “XMLHttpRequest” realizar o POST do recurso  “usuario“ para autenticação na API REST. O objeto JSON “JavaScript Object  Notation” apresentado abaixo,  para o endereço:  
http://45.55.144.89/fsapi/users/login 
    { 
        "email": "tlopes@gmail.com", 
        "password": "123456" 
    } 
Dica: para submeter dados json a um servidor web devemos utilizar o content type = application/json

aula_5: Após realizar o login considero um diferencial realizar a criação de um  usuário. A API para esse serviço está protegida por mecanismo para autenticação  baseada em token. 
URL: 
http://52.91.139.190/fsapi/users/auth/register-jwt
Método: 
POST 
JSON Exemplo 
{  
    "login": "alooooo@gmail.com", 
    "name": "Alooo Lopes", 
    "email":"alooo@gmail.com", 
    "password": "123456", 
    "confirma_password": "123456", 
    "idEmpresa": "13", 
  "Status": "Aprovado", 
   "role" : "Client", 
   "regId": "", 
    "status" : "Aprovado" 
} 
Header: Token para autenticação no serviço. Pegar do retorno do login  realizado no desafio anterior 


Lista_2

aula_1: Crie dois botões no HTML chamados: 'Verde'e 'Vermelho'. ao clicar neles, o style="background-color: {COR-SELECIONADA}" vai ser alterado dinamicamente Alterar-Style

aula_2: Crie uma função que recebe 2 parâmetros e retorna a soma deles.

aula_3: Crie uma função que recebe o ano de nascimento da pessoa informando se ela é maior de idade ou menor.

aula_4: Crie uma função que recebe o ano de nascimento da pessoa informando se ela é maior de idade ou menor.

aula_5: Crie uma função que informa se tem os caracteres 'dota' no parâmetro informado, exiba um alert em tela caso seja verdadeiro.
Ex: 'lol é melhor que dota' (verdadeiro)
Ex: 'lol é melhor que Dark Souls' (falso) / e Falso na vida real tmb.

aula_6: Peça ao usuário para digitar 5 números em uma caixa de texto. Calcule a média destes números digitadas pelo usuário e exiba em uma div.

Lista_3

aula_1: Crie o seguinte array: var deuses = ['Odin', 'Loki', 'Thor'] E Exiba a quantidade/comprimento que ele tem com a função .length

aula_2: Com o que foi feito no exercício anterior, exiba todos os nomes, dentro do html: <ul id="nomes"></ul>

aula_3: Seguindo do exercício 02, adicione o .sort para filtrar o array exibido no HTML. alfabeticamente

aula_4: Exiba a quantidade de letras que possuem o texto inserido ao clicar no botão.

Lista_4

aula_1: Dentro da div com o id 'resultado', escreva 1x ('Repetição')

aula_1_1: Dentro da div com o id 'resultado', escreva 2x ('Repetição').

aula_1_2: Dentro da div com o id 'resultado', escreva 20x ('Repetição'). (use o 'for')

aula_1_3: Dentro da div com o id 'resultado', escreva 5x ('Repetição'). (agora com forEach)

aula_1_4: Dentro da div com o id 'resultado', escreva 5x ('Repetição'). (agora com while)

aula_2: Dentro da div com o id 'resultado', escreva os números de 0 ~ 10 (escolha uma das opções utilizado no exercício anterior)

aula_3: Dentro da div com o id 'resultado', escreva os números pares até 20... (ex 2,4,6...20)

aula_04 - A partir do seguinte vetor e utilizando os métodos de array (map, reduce, filter e find):
const usuarios = [
{ nome: 'Caio', idade: 25, empresa: 'Google' },
{ nome: 'Tiago', idade: 35, empresa: 'Microsoft' },
{ nome: 'Felipe', idade: 30, empresa: 'Apple' },
];

aula_4_1: Utilizando o map crie uma variável que contenha todas idades dos usuários: [23, 15, 30]
