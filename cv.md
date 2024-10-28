###  rsschool-cv
<br>
<img src="../rsschool-cv/images/63f3708a-7b23-4c5b-8efc-a973df6a9869.jpg" style="width:120px; height:120px;" /> 

## Simuzar Fatullazade

## Front-end intern

> #### Contact information:
> 
>  Phone: +7 999 000 00 00  
>  E-mail: 000000@gmail.com  
>  Telegram: @janelame  
>  Discord: sima_40069 


#### About me

I am a professional linguist with experience working as a QA specialist in the field of translations. Currently I am studying web development. Having completed several courses on Codecademy (basic JavaScript, HTML and CSS), I enrolled in RS-School courses to further consolidate my knowledge, fill any gaps I have, and deepen my understanding of web development technologies.

Although I don't have experience working on IT projects yet, I aim to leverage my analytical skills, honed through my linguistic education and QA experience, to excel in the world of frontend development. My goal is to become a sought-after specialist in frontend development, creating high-quality and intuitive web interfaces. In the future, I plan to actively develop my skills and seek opportunities to work in innovative teams.

#### Skills and Proficiency
- HTML5, CSS3, JavaScript basics
- Git, GitHub
- VSCode
- React basics
- SQL basics

#### Code example:
#####Description:
Write a function that accepts a string, and returns the same string with all even indexed characters in each word upper cased, and all odd indexed characters in each word lower cased. The indexing just explained is zero based, so the zero-ith index is even, therefore that character should be upper cased and you need to start over for each word.

```javascript
function toWeirdCase(string){
  //TODO
  if (string === '') {
    return '';
  }
  const words = string.split(' ');
  
  const weirdCaseWords = words.map(word => {
    let weirdCaseWord = '';
    for (let i = 0; i < word.length; i++) {
      if( i % 2 === 0) {
        weirdCaseWord += word[i].toUpperCase();
      } else {
        weirdCaseWord += word[i].toLowerCase();
      }
    } return weirdCaseWord;
  }); return weirdCaseWords.join(' ');
  }

```
#### Projects:
[Audio player](https://rolling-scopes-school.github.io/simuzar-JSFEPRESCHOOL2024Q2/audio-player/)

#### Languages
- Russian (native)
- English (C1)
- Turkish (B1)
- Azeri (A2)
- German (A2)