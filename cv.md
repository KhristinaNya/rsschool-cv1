1. Khristsina Sycheuskaya
2. kristina19960712@gmail.com, никнейм на дискорд-сервере Khristina(@KhristinaNya)
3. I'm hardworking and responsible person. I like to get new experience, it's very interesting to know new things. I have been writing code on Delphi for 3 years and I want to study more popular language.    
4. JavaScript, Delphi, SQL
5. Weight for weight
The weight of a number will be the sum of its digits.
For example 99 will have "weight" 18, 100 will have "weight" 1.
Need a string sort by the "weight" of these numbers.
```js
 function sum(number) {
   return number.toString().split('').reduce((acc, value) => acc + +value, 0);
 }
 function orderWeight(strng) {
   return strng.split(" ").sort((a,b) => sum(a) - sum(b) || a.localeCompare(b)).join(' ');
 }
```
6. I work in the factory 3 years, my work relates to the support and developement software.
7. Brest State Technical University
8. A2