Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

#### Getting To Know String Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (4-5 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your own words and one sentence explain what this method does.

Example:

1. `charAt`

   - Parameter: (index) defaults to 0 - (number data type)
   - Return: character at specific index in the string (string data type)
   - Example:
     ```js
     let name = 'Arya Stark';
     name.charAt(2); //"y"
     let sentance = 'A quick brown fox jumped over a lazy dog';
     sentance(4); // "i"
     let houseName = 'Starks';
     houseName.charAt(0); // "S"
     ```
   - `charAt` accepts a index (number data type) and return the character on that index in the string.

2. `toUpperCase`
      parameter:(index) default to 0 -(number data type.)
      Return : character at specific index in the string(string data types.)
      ```js
       let username = "Jhon Snow";
       let tagline = "Software Developer";  
       username.toLowerCase(2);
       tagline.toLowercase();
       ```
       `toUppercase` accepts a index (number data type) and return the character on that index in the string.
3. `toLowerCase`
    parameter:(index) default to 0 -(number data type.)
      Return : character at specific index in the string(string data types.)
      ```js
       let firstname = "Jhon Snow";
       let proficient = "Software Developer";
       firstname.toUpperCase(2);
       proficient.toUppercase();
       ```
       `toLowercase` accepts a index (number data type) and return the character on that index in the string.
4. `trim`
       parameter:(index) default to 0 -(number data type.)
       Return : character at specific index in the string(string data types.)
      ```js
       let message = "    Hello World   " ;
       let proficient = "I am a fullstack software developers" ;
       message.trim();
      proficient.trim();
       ```
       `trim` accepts a index (number data type) and return the character on that index in the string it trim all the white spaces.
5. `trimEnd` it removes white spaces from start.
6. `trimStart` it removes white spaces from end.
7. `concat`
  ```js
       let message = "    Hello World   " ;
       let proficient = "I am a fullstack software developers" ;
       ;
       message.concat(" ",proficient);
       ```
8. `endsWith`
  ```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.endsWith('hello') ;
  tagline.endsWith('developers');
  ```

9. `includes`
```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.includes('hello') ;
  tagline.includes('developers');
  ```
10. `indexOf`
    ```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.indexof('e') ;
  tagline.indexof('you');
  ```
11. `lastIndexOf`
  ```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.lastindexof('e') ;
  tagline.lastindexof('you');
  ```
12. `padEnd`
   ```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.padEnd('10','.') ;
  tagline.padEnd('12','.');
  ```
13. `padStart`
 ```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.padStart('10','.') ;
  tagline.padStart('12','.');
  ```
14. `repeat`
 ```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.repeat("4") ;
  tagline.repeat("2");
  ```
15. `replace`
 ```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.replace("Campus","School") ;
  tagline.replace("you","we");
  ```
16. `slice`
```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.slice("0","5") ;
  tagline.slice("2","10");
  ```
17. `split`
```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.split("0") ;
  tagline.split("0");
  ```
18. `substring`
```js
  const username = "AltCampus";
  const tagline = "Everything you need to become a software developers";
  username.substring("0","5") ;
  tagline.substring("2","10");
  ```
