# MenuBits

O MenuBits é um inovador cardápio digital projetado para simplificar a operação de restaurantes. Oferece atualização fácil de preços, acesso rápido via QR Code, detalhes abrangentes dos produtos e estatísticas úteis de vendas. Para os clientes, proporciona atendimento ágil, sem os inconvenientes da sujeira dos cardápios tradicionais, além de opções exclusivas que só a tecnologia digital pode oferecer, elevando o conforto e a satisfação geral.

## Instruções de utilização

**Nossa aplicação backend e os bancos de dados já se encontram disponíveis na nuvem** <br />

-> Para acessar, você precisa: <br />

  1 - Acesse o Swagger para visualizar os endpoints:<br />
  https://menu-bits-backend.onrender.com/swagger/<br />

  2 - Abra o Postman e envie os endpoints que deseje verificar!<br />
  A URL base é: https://menu-bits-backend.onrender.com/<br />

  Exemplo de Endpoint: <br />
  (GET) https://menu-bits-backend.onrender.com/api/groups<br />

**Execução LOCAL** <br />

-> Para acessar a aplicação localmente, o passo-a-passo é:

1 - Instale o Visual Studio Code (https://code.visualstudio.com/)<br />
2 - Clone a aplicação com o **GIT CLONE**<br />
3 - Navegue até a pasta **BACKEND** dentro da estrutura do projeto (Cd SRC, Cd backend)<br />
4 - Execute o **NPM I** no terminal integrado<br />
5 - Execute os comandos para ajustar o banco de dados:<br />
    - npx prisma migrate dev<br />
    - npx prisma generate<br />
6 - Execute o NPM START, que a aplicação será iniciada.<br />

ARQUIVO .ENV que precisa ser adicionado na pasta BACKEND
<br />
{
PORT=8080
DATABASE_URL="postgres://menubits_user:jSOuTiBLdPQN9pwadTAOJK8i0zcbX6Qb@dpg-ck71vunq54js73cabhkg-a.oregon-postgres.render.com/menubits"
MONGO_DATABASE_URL="mongodb+srv://menubits:AmltDMmr9R6B17Iw@menubits.0tjqjw6.mongodb.net/?retryWrites=true&w=majority"
}
<br />
<br />
<br />
[+] Caso deseje executar o Prisma Studio para verificar o armazenamento dos dados no BD relacional, execute:<br />
    - npx prisma studio<br />

# Documentação

<ol>
<li><a href="docs/01-Documentação de Contexto.md"> Documentação de Contexto</a></li>
<li><a href="docs/02-Especificação do Projeto.md"> Especificação do Projeto</a></li>
<li><a href="docs/03-Metodologia.md"> Metodologia</a></li>
<li><a href="docs/04-Projeto de Interface.md"> Projeto de Interface</a></li>
<li><a href="docs/05-Arquitetura da Solução.md"> Arquitetura da Solução</a></li>
<li><a href="docs/06-Template Padrão da Aplicação.md"> Template Padrão da Aplicação</a></li>
<li><a href="docs/07-Programação de Funcionalidades.md"> Programação de Funcionalidades</a></li>
<li><a href="docs/08-Plano de Testes de Software.md"> Plano de Testes de Software</a></li>
<li><a href="docs/09-Registro de Testes de Software.md"> Registro de Testes de Software</a></li>
<li><a href="docs/10-Plano de Testes de Usabilidade.md"> Plano de Testes de Usabilidade</a></li>
<li><a href="docs/11-Registro de Testes de Usabilidade.md"> Registro de Testes de Usabilidade</a></li>
<li><a href="docs/12-Apresentação do Projeto.md"> Apresentação do Projeto</a></li>
<li><a href="docs/13-Referências.md"> Referências</a></li>
</ol>

