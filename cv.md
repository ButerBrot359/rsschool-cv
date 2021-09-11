# Temirov Batyrkhan

### Junior Frontend Developer

--------------------------------------------------------------------

### Contact information:

* __Place and date of birth:__ Kazakhstan,Pavlodar. 21/03/1997
* __Phone:__ +7(778)788-64-32
* __E-mail:__ batowka359@gmail.com
* __Telegram:__ @buterbrot359

--------------------------------------------------------------------

### Briefly About Myself:

Born and raised in the city of Pavlodar. I am interested in music, games and drawing. In 2019 I received my Bachelor's degree in Thermal Engineering. At the moment, I am actively learning programming.

--------------------------------------------------------------------
### Education

**_2015-2019_**\
* **Bachelor, Heat Power Engineer:** Almaty University of Power Engineer and Telecommunications (Almaty)\
**_2019-2022(expected)_**\
* **Programmer:** Hello Alem (School 42, Nur-Sultan)\

--------------------------------------------------------------------

### Hard Skills:

1) HTML5, CSS3
2) JavaScript, Golang, Rust, Python, SQL
3) Git, GitHub
4) VS Code
5) Docker

### Hard Skills:

* Creativity
* Adaptibility
* Management skills
* Technical skills
* Critical thinking
* Self-education

----------------------------------------------

### Work experience:

    Non-profit projects at Alem Programming School

#### Code example:

##### Get the Middle Character KATA from Codewars:

In this kata you're expected to sort an array of 32-bit integers in ascending order of the number of on bits they have.\

E.g Given the array [7, 6, 15, 8]\

7 has 3 on bits (000...0111)\
6 has 2 on bits (000...0011)\
15 has 4 on bits (000...1111)\
8 has 1 on bit (000...1000)\
So the array in sorted order would be [8, 6, 7, 15].\

In cases where two numbers have the same number of bits, compare their real values instead.\

E.g between 10 (...1010) and 12 (...1100), they both have the same number of on bits '2' but the integer 10 is less than 12 so it comes first in sorted order.\

Your task is to write the function sortBybit() that takes an array of integers and sort them as described above.\

Note: Your function should modify the input rather than creating a new array.\

```function sortByBit(arr) {
    arr.sort(function(a, b) {
        if (decToBin(a) == decToBin(b)) {
            return a - b
        } else {
            return decToBin(a) - decToBin(b);
        }
        
    });
    return arr
   
}

function decToBin(x) {
    return Number(x).toString(2).split('0').join('')
}```

----------------------------------------------

### Qualification courses

* __*2021 may:*__ Online course on Udemy. JavaScript from zero to expert

* __*2021 july:*__ Online course on Udemy. Websocket

* __*2021 september - now:*__ Rolling scope school. Front-end developer



