# Data-BMI
This is coding challenge from Jonas Schmedtmann class in Udemy

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
