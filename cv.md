<h1><span style="color:#3399ff">rsschool-cv</span></h1>

# Nataliya Pererva

## Junior Frontend Developer

### Contact information:
- **Phone:** +38-097-518-54-04
- **E-mail:** pererva.n[аt]gmail.com

### About Myself:

- I have experience in software sales
- Сomposed ten web-sites on Tilda and after this I decided that I wanted to be a front-end developer

### Skills and Proficiency:
- HTML5, CSS3
- Git, GitHub
- VS Code
- JavaScript Basics
- Canva
  
### Code example:
```
'use strict';
/**
 * @param {number} amount
 * @param {string} currency
 * @return {number}
 */
function countCommision(amount, currency) {
 let commision = 0;
 
 if (currency == 'UAH') {
   if (amount <= 1000) {
     commision = 2;
   } else {
     commision = 1;
   }
 }
 
 if (currency == 'USD') {
   if (amount <= 5000) {
     commision = 0.5;
   } else {
     commision = 0.25;
   }
 }

 if (currency == 'EUR') {
   if (amount <= 3000) {
     commision = 0.75;
   } else {
     commision = 0;
   }
 }

 return amount * commision / 100;
}

// examples
countCommision(20000, 'USD'); // ===> 50
countCommision(500, 'UAH'); // ===> 10
countCommision(2000, 'UAH'); // ===> 20
```

### Courses:
- [RS Schools Course «JavaScript/Front-end. Stage 0»](https://rs.school/js-stage0/) (in progress)
- [Gromcode Javascript-basics](https://gromcode.com/)

### Languages:
- English - pre-Intermediate
- Russian - Native
- Ukrainian - Native
