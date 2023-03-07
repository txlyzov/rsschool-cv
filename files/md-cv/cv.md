# CV#1. Markdown & Git

## Personal information:
**Name:** Timofey Hlyzov (passport version - Timophey Khlyzov) | 04/02/2000 <br />
**Phone:** A1 +375293716805 <br />
**Email:** txlyzov@gmail.com <br />
**Location:** Belarus, Minsk.

<details>
<summary>Spoiler (Photo).</summary>
<pre>
<img src="./cv-image.jpg"  width="30%">
</pre>
</details>
<br />


## Goal : 
Front-end React Developer in a team with more experienced Front-end developers.
<br />
<br />

## Stack: 
- JavaScript / Node JS / Typescript, 
- React, 
- HTML / CSS (SCSS) / Bootstrap, 
- Ant Design, 
- Figma,  
- SQL (MySQL,PostgreSQL) / NoSQL(MongoDB), 
- Java, 
- Angular,
- Spring Framework.
<br />
<br />

## IT experiences (Uses) - goal:
 - React application for warehouse management (React, JS, API, Figma, Prettier, ESLint) - studying react, creating react components and practice react;<br />

[[All development files]](https://github.com/txlyzov/warehouse-app)<br />

- React applications during Syberry Academy (React, JS/TS, API, And Design) - teamwork practice with FE React and BE teams;<br />

[internal project (х2)]<br />

- Simple react app for note displaying ( React, JS, API) - studying react and practice react,react hooks,JSX - copy of youtube course;

[[All development files(not cleaned)]](https://github.com/txlyzov/react-tutorials)<br />

- Image gallery (Angular, Typescript, Node JS, PostgreSQL, HTML \ CSS, Bootstrap, ESLint \ Prettier, Git Actions) - work with client and server communication,NodeJS and Angular practice;<br />

[[Front-end(Angular)]](https://github.com/txlyzov/web-angular-front)<br />
[[Back-end(NodeJS)]](https://github.com/txlyzov/web-angular-back)<br />

- Bot for Discord (Java, Spring, Discord API, MongoDB, WebSockets, API, HTML / CSS, Bootstrap, Thymeleaf) -  processing incoming information from the other source and sending information to the messenger servers based on their needs, which are displayed on the web page;<br />

[[Bot files]](https://github.com/txlyzov/Bot-project/tree/main/ETRA)<br />
[[All development files]](https://github.com/txlyzov/Bot-project)<br />

- Udemy.com cource (HTML5, CSS3, Bootstrap 4, Javascript, React JS, Angular, NodeJS, MongoDB) - studying;<br />

[[HTML5, CSS3, Bootstrap 4]](https://txlyzov.github.io/test.github.io/)<br />
[[All development files]](https://github.com/txlyzov/trnng)<br />

- University labs mainly related to work on creating desktop applications, also including MySQL, PostgreSQL.


## Education: 
- Syberry academy - front end [[1]](https://drive.google.com/file/d/1jUld5HtoZ3KcmstV3pnRIRFqkfMqZ9Us/view?usp=sharing);
- Belarusian State University of Informatics and Radioelectronics, Faculty of Information Technologies and Control, Minsk, 2021, Bachelor / System engineer;

## Code example:

```js
// Task:

// The marketing team is spending way too much time typing in hashtags.
// Let's help them with our own Hashtag Generator!

// Here's the deal:
// It must start with a hashtag (#).
// All words must have their first letter capitalized.
// If the final result is longer than 140 chars it must return false.
// If the input or the result is an empty string it must return false.
// Examples
// " Hello there thanks for trying my Kata"  =>  "#HelloThereThanksForTryingMyKata"
// "    Hello     World   "                  =>  "#HelloWorld"
// ""                                        =>  false

function generateHashtag(str) {
  str = str.split(" ").filter((f) => {
    return f !== "";
  });
  if (str.length === 0) {
    return false;
  }

  final =
    "#" + str.map((word) => word[0].toUpperCase() + word.substring(1)).join("");

  return final.length > 140 ? false : final;
}

console.log(generateHashtag("Do We have A Hashtag"));
console.log(generateHashtag("code" + " ".repeat(140) + "wars"));
```

## Languages: 
- Russian - native speaker
- English - B1 (Speech understanding, can chat).


## Experience:
- React front end developer - Syberry (08.2022 - 12.2022);
- Junior javascript developer - Itransition (16.12.2021 - 18.03.2022);
- Practice during the university - Itransition (04.2021).


## Preference:
Web development.


## Recommendation:
Itransition. [[1(rus)]](https://docs.google.com/document/d/1VcZT7wuMuwht_W_yDXAVstSDJI1IyzUWoY4kmOXhdoo/edit?usp=sharing)


## Additional links: 
Telegram - https://t.me/z63yuuB4r1DS <br />
LinkedIn - https://www.linkedin.com/in/txlyzov/ <br />
GitHub - https://github.com/txlyzov
