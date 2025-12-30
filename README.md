# Data-BMI
Solution for Jonas Schmedmann's Java Script COding Challenge #1: Calculating BMI for two people and comparing result.

//Data
const massMark = 78;
const heightMark = 1.69;
const massJohn = 92;
const heightJohn = 1.95;

// BMI Formula = mass / (height **2)
const BMIMark = massMark / (heightMark ** 2);
const BMIJohn = massJohn / (heightJohn ** 2);

// Who is BMI Higher
const markHigherBMI = BMIMark > BMIJohn;

console.log(BMIMark, BMIJohn, markHigherBMI);
