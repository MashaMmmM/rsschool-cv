[rsschool-cv](http://127.0.0.1:5500/Masha%20CV/index.html)

# Mary Melnikova
## Contacts
* Phone: +375(29)6265251
* Email: marymelnikova2000@gmail.com
* GitHub: [MashaMmmM](https://github.com/MashaMmmM)
* Location: Belarus, Minsk
## About me
I like to learn new things every day. I love creative work such as drawing, knitting, etc. I love reading books and comics, and doing sports.

## Skills
* HTML and CSS
* JavaScript
* English A2+ level
* Figma
* Photoshop
## Education
* Belarusian State Technological University
## Code example 
```
let mass = process.argv.slice(2),
    length = mass.length,
    hach = [],
    result = [];
if (length > 0) {
    for (let i = 0; i < length; i++) {
        hach[i] = 0;

        for (let j = 0; j < mass[i].length; j++) {
            hach[i] += mass[i].codePointAt(j);
        }
    }
    for (let i = 0; i < length; i++) {
        result[i] = hach.filter(value => value == hach[i]).length;
    }
    let maxHash = hach[result.indexOf(Math.max(...result))];
    for (let i = 0; i < hach.length; i++) {

        if (hach[i] == maxHash) {
            console.log(mass[i]);
        }
    }
}
```
## English
A2+ level