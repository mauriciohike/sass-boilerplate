# Sass Boilerplate


[![made with hearth by mauriciohike](https://img.shields.io/badge/made%20with%20%F0%9F%92%9B%20by-mauriciohike-%237159c1)](https://github.com/mauriciohike)


Boilerplate created to facilitate the initial structure of sass projects.

## 🔧 Usage
I created the compile script with **node-sass**, need to run this command:

    npm install

Then:

    npm run build:scss


The compiled file will be in **css** folder.

## 📂 Folder Structure
Inspirated in **7-1 Pattern** (just excluding the **vendor** folder), this is the folder structure: 

    scss/
    |
    |– base/
    |   |– _reset.scss        
    |   |– _typography.scss   
    |
    |– utilities/
    |   |– _variables.scss    
    |   |– _functions.scss    
    |   |– _mixins.scss       
    |
    |– components/
    |   |– _buttons.scss      
    |
    |– layout/
    |   |– _navigation.scss   
    |   |– _grid.scss         
    |   |– _header.scss      
    |
    |– pages/
    |   |– _home.scss         
    |   |– _about.scss        
    |   |– _contact.scss      
    |
    |– themes/
    |   |– _theme.scss       
    |   |– _admin.scss        
    |
    `– main.scss