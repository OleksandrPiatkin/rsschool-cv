# Oleksandr Piatkin
<em>I'm a graduate of Gdansk University of Technology. 
Programming is truly a passion of mine, and right now I am 
improving my skills in JavaScript.</em>
<br>

## Contact
<img src="./img/GitHub-Mark-32px.png" alt="Git logo" width="14"/> [github.com/OleksandrPiatkin](github.com/OleksandrPiatkin)<br>
<span style='color: black;' width="14">&#9993;</span> oleksandr.piatkin@gmx.com <br>
<span style='color: black;' width="14">&#9742;</span> (+48) 574 576 388 <br>
<img src="./img/pngegg.png" alt="Map logo" width="14"/> 80-438, Gdansk <br>
<br>

## Skils
- JavaScript
- Semantic HTML, SCSS
- Basic knowledge:
    - React.js
    - Python
    - Git
    - Photoshop
    - Webpack
    - Flask
<br>

## My JS code sample (method of a Class)
<br>

```
async drawCards(count) {
    const response = await fetch(`${baseUrl}/${this.deckId}/draw/?count=${count}`);
    if (!response.ok) {
        throw new Error('Response status error.');
    }
    const data = await response.json();
    if (data.success) {
        data.cards.forEach(element => {
            let card = new Card(element.value, element.image);
            this.cards.push(card);
            let player = document.getElementById(`player-${this.id}`);
            card.render(player);
        });
        this.checkPoints();
        this.renderPoints();
    } 
    else {
        throw "Exception when drawing cards.";
    }
}
``` 

<br>

## Education
02.2017 - 12.2020 <br>
**Gdansk University of Technology** <br>
Masters degree in Power Engineering <br>

### **Master's degree project**
<u>Topic: An application for birds sound recognition</u> <br>
Project is implemented  in Python, recognition  occur by machine learning algorithms, using libraries such a flask, sklearn, librosa, numpy etc. <br>
Source links: <br>
- [App Front-end](https://github.com/OleksandrPiatkin/Birder) <br>
- [API](https://github.com/OleksandrPiatkin/Birder-API)

### **Courses**
"The Complete Web Developer in 2020: Zero to Mastery" <br>
Completed 03.2020 <br>
Organized by: Udemy, Andrei Neagoie <br>
35h Flexbox, CSS Grid, Bootstrap 4, Advanced JavaScript, 
HTTP/JSON/AJAX, Asynchronous JavaScript, React + Redux, etc. 
& more than 100h homework. <br>
## Lenguages
- English A2 (one year practice during internship at "The Chef's Garden", US)
- Polish B2
- Russian/Ukrainian - native
<br>
<section style='font-size: 0.8em; text-align: center;'><i>In accordance with art. 6 (1) a and b. Regulation (EU) 2016/679 of the European Parliament and of the Council of 27 April 2016  on the protection of natural persons with regard to the processing of personal data and on the free movement of such data, and repealing  Directive 95/46/EC (General Data Protection Regulation) hereinafter ‘GDPR’. I agree to have: my personal data, education and employment history proceeded for the purposes of current and future recruitment processes.</i></section>


