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
