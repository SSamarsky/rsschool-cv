# Sergey Samarskiy

## *Junior Frontend Developer*

## Contacts
* **Location**: Russia, Nizhny Novgorod region, Sarov
* **E-mail**: js.samarsky@gmail.com
* **Phone**: +79506215056
* **Github**: [@SSamarsky](https://github.com/SSamarsky?tab=repositories)

## Summary
I am 28 years old. <br>
I work as a process engineer at a factory. <br>
I am studying JavaScript/Front-End development. <br>
I love to learn and improve my programming skills. <br>
I am looking for a job in a friendly team with interesting tasks.

## Skills
* CSS3
* HTML5
* JavaScript
* Git and GitHub
* Figma and Adobe Photoshop

## Code Example
**RGB To Hex Conversion** <br>
JavaScript:
```
function rgb(r, g, b) {
    let hexColor = '';
    function transformNum(num) {
        let str = '';
        if (num > 255) {
            num = 255;
        } else if (num < 0) {
            num = 0;
        }
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

