# Sergey Samarsky

## *Frontend Developer*

## Contacts

* **Location**: Russia, Nizhny Novgorod region, Sarov
* **E-mail**: js.samarsky@gmail.com
* **Telegram**: @S_Samarsky
* **Phone**: +79506215056
* **Github**: [SSamarsky](https://github.com/SSamarsky)

## Summary

I am a frontend developer. <br>
I like Front-end, but my heart is open to other directions. <br>
I've been learning JavaScript since 2021. There are several small but interesting projects in my portfolio. <br>
I am always learning and developing. I strive to write clean and understandable code. I want to become a senior front-end developer.

## Skills

* **HTML**: structural and semantic tags, validation;
* **CSS**: preprocessor SCSS, perfect pixel, flexbox and grid layout, adaptive and responsive layout, cross-browser;
* **JavaScript**: ES6 and higher, DOM, AJAX, Async JavaScript;
* **Git and GitHub**: basic understanding of git fundamentals;
* **Tools**: basic knowledge of Webpack, basic knowledge of browser tools (Chrome DevTools: Elements, Console, Network, Sources);
* **Figma and Adobe Photoshop**: website layout

## Soft Skills

* Able to work effectively under supervision;
* Ability understand task requirements;
* Able to plan his/her work time (Self-management, Time-management);
* Able easy to fit into the team

## Code Example
**RGB To Hex Conversion** <br>
JavaScript:
```
function rgb(r, g, b) {
    let hexColor = '';

    function transformNum(num) {
        let str = '';
        
        if (num > 255) num = 255;
        else if (num < 0) num = 0;

        if (num < 16) {
            str = str + 0 + num.toString(16);
            return str;
        } else {
            str = str + num.toString(16);
            return str;
        }
    }

    hexColor = hexColor + transformNum(r) + transformNum(g) + transformNum(b);
    return hexColor.toUpperCase();
} 
```
## Education
**University**: Nizhny Novgorod State Technical University n.a. R.E. Alekseev  
**Higher education**: master's degree  
**Field of Study**: 22.04.01 Material Science and Material Technologies

## Courses
* [**The Rolling Scopes**](https://rs.school/js/): JS / FRONT-END. STAGE 0
* [**Learn.javascript**](https://learn.javascript.ru/)<br>
* Free courses on different youtube channels

##  Books
* Head First JavaScript Programming. Eric Freeman, Elisabeth Robson
* Grokking Algorithms: An illustrated guide for programmers and other curious people. Aditya Y. Bhargava
* You Don't Know JS: Get Started. Kyle Simpson
* You Don't Know JS: Scope & Closures. Kyle Simpson
* Eloquent JavaScript. Marijn Haverbeke