![avatar](/assets/images/avatar.png)

# Dzmitry Maltsau

## JS Developer

### Hello!

### I'm 39 years old. Graduated from Gomel State Technical University in 2005. I used to work in oil industry and now I want to learn a new specialty - JavaScript developer.

### Birth date: 28.04.1983

### City of residence: Gomel, Belarus

### Phone: +375447617586

### E-mail: emeraldwhistler.dm@gmail.com

### GitHub: https://github.com/Maltsau

### LinkedIn: https://linkedin.com/in/dzmitry-maltsau-58079a251

### Codewars: https://www.codewars.com/users/Maltsau

## Experience

- ### Design engineer (constructor)

  #### _oct. 2005 – oct. 2007_

  #### “Gomel Plant “Communalnik”, Gomel

- ### Well survey engineer, lead engineer, head of geophysical party
  #### _oct. 2007 – nov. 2022_
  #### “Production Association “Belorusneft”, Department of Field Geophysical Research, Rechitsa

## Education

- ### **Higher education**

#### **Gomel State Technical University** _jun. 2005_

#### Qualification – mining engineer

#### Spatiality – development and operation of oil and gas fields

- ### **Additional education**

#### **JavaScript course, White Lynx Center**, Gomel _aug. 2021_

## TechStack

### JavaScript, TypeScript, HTML, CSS, ReactJS, Next.js, Zustand, Styled-Components, ReactQuery

## Languges

- ### Russian – native
- ### Belarusian – fluent
- ### English - intermediate

## Participations

### https://www.clookva.com/

## Example of code

```javascript function solution(number){
  const ROMAN_RULES = {
    1: "I",
    2: "II",
    3: "III",
    4: "IV",
    5: "V",
    6: "VI",
    7: "VII",
    8: "VIII",
    9: "IX",
    10: "X",
    20: "XX",
    30: "XXX",
    40: "XL",
    50: "L",
    60: "LX",
    70: "LXX",
    80: "LXXX",
    90: "XC",
    100: "C",
    200: "CC",
    300: "CCC",
    400: "CD",
    500: "D",
    600: "DC",
    700: "DCC",
    800: "DCCC",
    900: "CM",
    1000: "M",
    2000: "MM",
    3000: "MMM"
  };
  const romanNumber = [...number.toString()].map((simbol)=>Number(simbol)).reverse().
                        map((number, index)=> number*10**index).reverse().
                        map((item)=> ROMAN_RULES[item]).join('');
  return romanNumber;
}
```
