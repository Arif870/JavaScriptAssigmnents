# JavaScriptAssigmnents

### Enter your age and find your Category
```
function human(age) {
    if (age >= 0 && age <= 10) {
        return "Your age is " + age + " you are a Baby";
    } else if (age >= 11 && age <= 20) {
        return "Your age is " + age + " you are a Teenager";
    } else if (age >= 21 && age <= 35) {
        return "Your age is " + age + " you are a Young";
    } else if (age >= 36 && age <= 120) {
        return "Your age is " + age + " you are a old";
    } else {
        return "I think he/she is no more";
    }
}
```
<img width=500 src="images/ass1.png">
<img width=500 src="images/ass2.png">

### For loop print 1 to 1000 but 700 to 900 will not be printed
```
for (let i = 1; i <= 1000; i++) {
    if (i >= 700 && i <= 900) {
        continue;
    }
    console.log("value = " + i);
}
```


<img width=500 height=500 src="images/ass3.png">
