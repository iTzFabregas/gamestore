# Projeto de Desenvolvimento da GameStore
| Colaboradores    | 
| -------- |
| [iTzFabregas (Fabrício Sampaio)](https://github.com/iTzFabregas) | 
| [artP2 (Arthur Pin)](https://github.com/artP2) | 
| [rubenszinho (Samuel Rubens)](https://github.com/rubenszinho) |
### Requisitos
Os requisitos iniciais foram fornecidos na tarefa e incluem a existência de dois tipos de usuários (Clientes e Administradores), gerenciamento de produtos e serviços, carrinho de compras e a implementação de uma funcionalidade específica para a loja.
### Descrição do Projeto
O projeto foi desenvolvido utilizando HTML, CSS e JavaScript. Foi implementado um layout responsivo, que se adapta a diferentes tamanhos de tela e dispositivos. A estrutura das páginas inclui uma barra de navegação, conteúdo principal e rodapé. Além disso, foi criado um sistema de troca de temas (escuro, claro e solarizado) e um protótipo de dados a serem consumidos, que no caso foram intermediados pela RAWG API, que já é especializada em jogos. Também foram implementadas todas as funcionalidades da parte do cliente, como: inscrição, login, busca, carrinho, checkout, entre outros.
![Diagrama do Projeto](https://github.com/rubenszinho/gamestore/blob/develop/public/diagram.png)
### Comentários sobre o código
O código foi organizado em arquivos separados para facilitar a manutenção e a legibilidade. Os arquivos de estilo (CSS) foram separados por componentes, como navbar, game card, footer, entre outros. Os scripts (JavaScript) também foram separados por funcionalidade. A modularização e a redução de variáveis globais tornaram o código mais robusto e fácil de manter.
### Plano de Testes
Testes manuais do funcionamento.
#### Fluxo de Admin
Credenciais: **email:** admin@admin.com, **senha:** admin
- **Gerenciamento de jogos:** Logar como admin → Adicionar novo jogo pelo botão "+" na homepage → Editar ou excluir jogo pelo botão "lápis" na página de detalhes do jogo.- **Gerenciamento de usuários:** Logar como admin → Ir para a página de administração → Abrir a lista de usuários → Editar ou remover um usuário pelos botões.
#### Fluxo de Usuário
- **Gerenciamento do perfil:** Registrar usuário na página de login → Fazer login → Editar usuário na página de perfil → Fazer logout.- **Esqueceu senha:** Clicar em "esqueceu a senha" na página de login → Criar nova senha → Testar login com a nova senha.- **Carrinho:** Abrir um jogo → Adicionar ao carrinho → Fazer checkout (o carrinho permanece entre as sessões do usuário, então pode fazer logout e login antes de fazer o checkout).- **Buscar jogos:** Digitar na barra de busca e clicar no botão → Conferir os resultados.
### Procedimentos de Compilação
É necessário ter o [MongoDB](https://www.mongodb.com/try/download/community) e o [Node.js](https://nodejs.org/en/download) instalados na sua máquina e seguir os seguintes passos:
1. Clone o repositório:
   ```bash   git clone https://github.com/rubenszinho/gamestore.git   ```
2. Acesse o diretório do projeto:
   ```bash   cd gamestore   ```
3. Instale as dependências:
   ```bash   npm install --force   ```
4. Inicie a aplicação:
   ```bash   npm start   ```
### Screenshots
A seguir, estão capturas de tela do projeto GameStore em suas versões nos temas claro e escuro.
#### Tema Escuro
1. **Adicionar Jogo (Admin)**
   ![Adicionar Jogo (Admin) - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/admin-game-add.html-dark.png)
2. **Categoria**
   ![Categoria - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/category-dark.png)
3. **Editar Perfil**
   ![Editar Perfil - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/edit-profile-dark.png)
4. **Detalhes do Jogo**
   ![Detalhes do Jogo - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/game-details-dark.png)
5. **Página Inicial (Admin)**
   ![Página Inicial (Admin) - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/index-admin-dark.png)
6. **Página Inicial**
   ![Página Inicial - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/index-dark.png)
7. **Login**
   ![Login - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/login-dark.png)
8. **Meu Carrinho**
   ![Meu Carrinho - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/my-cart-dark.png)
9. **Registro**
   ![Registro - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/register-dark.png)
10. **Perfil do Usuário**
    ![Perfil do Usuário - Tema Escuro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/user-profile-dark.png)
#### Tema Claro
1. **Adicionar Jogo (Admin)**
   ![Adicionar Jogo (Admin) - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/admin-game-add.html.png)
2. **Categoria**
   ![Categoria - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/category.png)
3. **Editar Perfil**
   ![Editar Perfil - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/edit-profile.png)
4. **Detalhes do Jogo**
   ![Detalhes do Jogo - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/game-details.png)
5. **Página Inicial (Admin)**
   ![Página Inicial (Admin) - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/index-admin.png)
6. **Página Inicial**
   ![Página Inicial - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/index.png)
7. **Login**
   ![Login - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/login.png)
8. **Meu Carrinho**
   ![Meu Carrinho - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/my-cart.png)
9. **Registro**
   ![Registro - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/register.png)
10. **Perfil do Usuário**
    ![Perfil do Usuário - Tema Claro](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/user-profile.png)
