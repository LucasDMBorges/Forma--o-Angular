# FormacaoAngular
# GatitoBook: uma rede social para Gatos

Projeto do curso da Formação ANGULAR da Alura.

🔨 Funcionalidades do projeto



✔️ Técnicas e tecnologias utilizadas


 - Começamos um projeto utilizando o angular/cli como ferramenta de apoio em todo nosso fluxo de trabalho. Utilizando a opção --strict, 
 ligamos mais verificações de tipo no nosso projeto, melhorando logo na largada a nossa qualidade do nosso código.
- Foi utilizado o Bootstrap como framework de CSS global para nossa aplicação.
- Com a técnica do lazy loading, melhoramos o carregamento inicial da nossa aplicação.
- Usei para interagir com nosso backend o serviço HttpClient do Angular.
- Foi usado o formulário do tipo Template Driven, em que toda a montagem e a regra de negócio ficam no arquivo de template, e o Angular 
realiza o controle do modelo de dados utilizando o componente ngModel.
- Utilizei a técnica de formulários reativos, em que nós temos um pouco mais de configurações, mas ganhamos mais possibilidades e controle sobre o formulário.
- Criei o serviço de cadastro de novo usuário e utilizei a boa prática de criar uma interface para o retorno do backend e assim ter melhor produtividade e menos erros.
- Usei a classe utilitária Validators, padrão do Angular.
- Usei uma validação customizada para um campo com isso aprendi quais são os requisitos para uma função ser reconhecida como validação no Angular.Também usei em 
uma função de validação que avaliava mais do que um campo do nosso formulário.Por fim, criei uma validação que consulta o backend da nossa aplicação e aprendi sobre 
os operadores RXJS, uma biblioteca poderosa que o Angular utiliza.
- Comecei a tratar as informações do nosso usuário que o backend nos retorna na forma de um token JWT (Json Web Token).Instalei uma biblioteca que nos ajuda a trabalhar
com esse tipo de dado e criamos um serviço exclusivamente para tratar a gravação e recuperação do token.Criei também um serviço que representa as operações com o 
usuário logado e nesse serviço decodificamos e fazemos o uso do objeto Subject do RXJS para propagar as alterações das informações do usuário.Por fim, criei o cabeçalho
e rodapé da nossa interface interagindo com esse serviço de Usuário.

🛠️ Abrir e rodar o projeto

Após clonar esse repositório será necessário entrar na pasta API e usar o comando npm i e npm start para rodar o backend. Depois dessa instalação abra a pasta gatitobook e 
repita os comando npm i e npm start ou utilize npm i e depois ng s -o.
