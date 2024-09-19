<kbd>[<img title="Português (Brasil)" alt="Português (Brasil)" src="https://cdn.statically.io/gh/hjnilsson/country-flags/master/svg/br.svg" width="22">](README.pt_br.md)</kbd>
# Projeto de Desenvolvimento da GameStore
| Collaborators    | 
| -------- |
| [iTzFabregas (Fabrício Sampaio)](https://github.com/iTzFabregas) | 
| [artP2 (Arthur Pin)](https://github.com/artP2) | 
| [rubenszinho (Samuel Rubens)](https://github.com/rubenszinho) |
# GameStore Development Project
### Requirements
The initial requirements were provided in the task and include the existence of two types of users (Customers and Administrators), product and service management, a shopping cart, and the implementation of a specific functionality for the store.
### Project Description
The project was developed using HTML, CSS, and JavaScript. A responsive layout was implemented, adapting to different screen sizes and devices. The structure of the pages includes a navigation bar, main content, and footer. Additionally, a theme-switching system (dark, light, and solarized) was created, and a data prototype to be consumed, which in this case was intermediated by the RAWG API specialized in games. All client-side functionalities were also implemented, such as registration, login, search, cart, checkout, among others.
![Project Diagram](https://github.com/rubenszinho/gamestore/blob/develop/public/diagram.png)
### Comments on the Code
The code was organized into separate files to facilitate maintenance and readability. The style sheets (CSS) were separated by components, such as navbar, game card, footer, among others. The scripts (JavaScript) were also separated by functionality. Modularization and reduction of global variables made the code more robust and easier to maintain.
### Test Plan
Manual testing of functionality.
#### Admin Flow
Credentials: **email:** admin@admin.com, **password:** admin
- **Game Management:** Log in as admin → Add a new game using the "+" button on the homepage → Edit or delete a game using the "pencil" button on the game details page.- **User Management:** Log in as admin → Go to the admin page → Open the list of users → Edit or remove a user using the buttons.
#### User Flow
- **Profile Management:** Register a user on the login page → Log in → Edit user on the profile page → Log out.- **Forgot Password:** Click on "forgot password" on the login page → Create a new password → Test the new password.- **Cart:** Open a game → Add to cart → Proceed to checkout (the cart persists between user sessions, so you can log out and log back in before checking out).- **Search Games:** Type in the search bar and click the button → Check the results.
### Build Procedures
You need to have [MongoDB](https://www.mongodb.com/try/download/community) and [Node.js](https://nodejs.org/en/download) installed on your machine and follow these steps:
1. Clone the repository:
   ```bash   git clone https://github.com/rubenszinho/gamestore.git   ```
2. Navigate to the project directory:
   ```bash   cd gamestore   ```
3. Install the dependencies:
   ```bash   npm install --force   ```
4. Start the application:
   ```bash   npm start   ```
### Screenshots
Below are screenshots of the GameStore project in its dark and light theme versions.
#### Dark Theme
1. **Add Game (Admin)**
   ![Add Game (Admin) - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/admin-game-add-dark.png)
2. **Category**
   ![Category - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/category-dark.png)
3. **Edit Profile**
   ![Edit Profile - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/edit-profile-dark.png)
4. **Game Details**
   ![Game Details - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/game-details-dark.png)
5. **Home Page (Admin)**
   ![Home Page (Admin) - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/index-admin-dark.png)
6. **Home Page**
   ![Home Page - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/index-dark.png)
7. **Login**
   ![Login - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/login-dark.png)
8. **My Cart**
   ![My Cart - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/my-cart-dark.png)
9. **Register**
   ![Register - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/register-dark.png)
10. **User Profile**
    ![User Profile - Dark Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/dark/user-profile-dark.png)
#### Light Theme
1. **Add Game (Admin)**
   ![Add Game (Admin) - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/admin-game-add.png)
2. **Category**
   ![Category - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/category.png)
3. **Edit Profile**
   ![Edit Profile - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/edit-profile.png)
4. **Game Details**
   ![Game Details - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/game-details.png)
5. **Home Page (Admin)**
   ![Home Page (Admin) - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/index-admin.png)
6. **Home Page**
   ![Home Page - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/index.png)
7. **Login**
   ![Login - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/login.png)
8. **My Cart**
   ![My Cart - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/my-cart.png)
9. **Register**
   ![Register - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/register.png)
10. **User Profile**
    ![User Profile - Light Theme](https://raw.githubusercontent.com/rubenszinho/gamestore/develop/public/mockup/light/user-profile.png)
