Automação de Testes com Cypress
Este repositório contém o desenvolvimento de testes automatizados de ponta a ponta (E2E) para a plataforma ServeRest. O objetivo deste projeto é validar fluxos críticos de usuário, garantindo a qualidade e estabilidade da interface.

Cenários Implementados
Atualmente, o projeto cobre os fluxos de autenticação:

Login com sucesso: Valida o acesso correto à plataforma e a transição para a lista de compras.

Login com falha: Garante que mensagens de erro adequadas sejam exibidas ao inserir credenciais inválidas.

Tecnologias Utilizadas
Cypress: Framework principal para automação.

JavaScript: Linguagem base dos scripts.

Node.js: Ambiente de execução.

Como Executar o Projeto
Clone este repositório:
git clone https://github.com/gabrielfoganholi/cypress-login-test.git

Instale as dependências:
npm install

Abra a interface do Cypress:
npx cypress open

Boas Práticas Aplicadas
Uso de seletores robustos (data-testid) para evitar testes quebradiços.

Organização de testes em cenários positivos e negativos.

Estruturação de código limpa e legível.
