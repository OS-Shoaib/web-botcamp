# JavaScript

Created: Feb 22, 2021 2:23 AM

---

[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[rwaldron/idiomatic.js](https://github.com/rwaldron/idiomatic.js)

```jsx
alert("Hello");
```

![JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_143342.png](JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_143342.png)

```jsx
typeof(23);
//  --> "number"
```

```jsx
prompt("What is your name?")
```

![JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_144406.png](JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_144406.png)

```jsx
var myName = "shoaib";
```

![JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_144709.png](JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_144709.png)

 

```jsx
var name = "Angela";
name.length;
// --> 6
```

```jsx
var name = "Angela";
name.slice(0,1);
// --> A
```

```jsx
var name = "Angela";
name.toUpperCase();
// --> ANGELA
name.toLowerCase();
// --> angela
```

Functions

![JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_204451.png](JavaScript%20146d765e7cea40679220ad5b9e744210/Screenshot_2021-03-06_204451.png)

print data to console - for debugging almost

```jsx
console.log("move")
```

Round Down

```jsx
Math.floor(1.6);
```

Function

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-12h08m47s536.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-12h08m47s536.png)

Power

```jsx
Math.pow(base, exponent);
```

Round

```jsx
Math.round(2.5);
```

Random 

```jsx
var n = Math.random();
```

[Math.random()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-14h52m28s974.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-14h52m28s974.png)

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-14h52m35s345.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-14h52m35s345.png)

It never reaches 1

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-14h52m01s484.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-14h52m01s484.png)

A way to get a random Integer

To get 6 as the max - not included number

```jsx
var n = Math.random();
n = n*6;
// min is 0 max is 5  
n = Math.floor(n); 
// to include 6 and remove 0 
n = Math.floor(n)+1;
console.log(n);
```

[https://www.youtube.com/watch?v=GtOt7EBNEwQ](https://www.youtube.com/watch?v=GtOt7EBNEwQ)

Pseudorandom number generators | Computer Science | Khan Academy

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-16h16m37s696.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-16h16m37s696.png)

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-16h16m49s960.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-16h16m49s960.png)

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-16h16m59s310.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-16h16m59s310.png)

IF statement

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-21h23m04s240.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-21h23m04s240.png)

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-21h35m34s449.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-21h35m34s449.png)

```jsx
if (ls === 100){
	alert("You are crazy");
}else{
	alert("Try harder");
}
```

```jsx
if (ls > 70){
	alert("You are crazy");
}else{
	alert("Try harder");
}
```

Difference between `===` and `==` 

```jsx
var a = 1;
var b = "1";

if (a === b) {
	console.log("yes")
} else {
	console.log("no")
}

// --> no
```

compare the value and data type

```jsx
var a = 1;
var b = "1";

if (a == b) {
	console.log("yes")
} else {
	console.log("no")
}

// --> yes
```

Ignore data type - compare the value only

Combining Comparators

![JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-22h31m38s319.png](JavaScript%20146d765e7cea40679220ad5b9e744210/vlcsnap-2021-03-07-22h31m38s319.png)

multi  options using IF

```jsx
if (ls > 70){
	alert("You are crazy");
}

else if (ls > 30 && ls <= 70){
	alert("message");
}

else{
	alert("Try harder");
}
```

## Array

```jsx
var guest = ["A", "B", "C"];

console.log(guest);

console.log(guest.length); // --> 3

console.log(guest[0]); // --> A
```

```jsx
var guestName = prompt("What is your name ? ");
guest.includes(guestName) // --> True or False
```

```jsx
var output = [];
output.push(1); // add 1 to the array -- at the end
output.pop; // remove last item from the array
```

Challenge One —Fizz-Buzz:

```jsx
var ooutput = [];
var count = 1;

function fizzBuzz() {
	output.push(count);

	if(count % 3 === 0 && cout % 5 === 0) {
		output.push("FizzBuzz");
	}
	else if (count % 3 === 0) {
		output.push("Fizz");
	}
	else if(cout % 5 === 0) {
		output.push("Buzz");
	}
	else {
		output.push(count);
	}
	
	count++;
	console.log(output);
}
```

Challange Two — Random selection

```jsx

function whosPaying(names){
	var numOfPeople = names.lenght;
	var randomPersonPesotion = Math.floor(Math.random() * numberOfPeople) // 0 - 0.99999 --> 0 - 4
	var randomPerson = names[randomPersonPesotion]
	return randomPerson + " is going to buy lunch today!"
}

names = ["Angela", "Ben", "Jenny", "Michael", "Chloe"];
```

## Loops

![JavaScript%20146d765e7cea40679220ad5b9e744210/13._Control_Statements_While_Loops.mp4_20210324_144320.104.jpg](JavaScript%20146d765e7cea40679220ad5b9e744210/13._Control_Statements_While_Loops.mp4_20210324_144320.104.jpg)

While Loop

![JavaScript%20146d765e7cea40679220ad5b9e744210/15._Control_Statements_For_Loops.mp4_20210324_151711.591.jpg](JavaScript%20146d765e7cea40679220ad5b9e744210/15._Control_Statements_For_Loops.mp4_20210324_151711.591.jpg)

For Loop

## While Loops

## Foor Loop

```jsx
var ooutput = [];
var count = 1;

while(count <= 100){
	function fizzBuzz() {
		if(count % 3 === 0 && cout % 5 === 0) {
			output.push("FizzBuzz");
		}
		else if (count % 3 === 0) {
			output.push("Fizz");
		}
		else if(cout % 5 === 0) {
			output.push("Buzz");
		}
		else {
			output.push(count);
		}
		count++;
	}
	console.log(output);
}
```

```jsx
var ooutput = [];

function fizzBuzz() {
	for(var count = 1; count < 101; count++;){
		if(count % 3 === 0 && cout % 5 === 0) {
			output.push("FizzBuzz");
		}
		else if (count % 3 === 0) {
			output.push("Fizz");
		}
		else if(cout % 5 === 0) {
			output.push("Buzz");
		}
		else {
			output.push(count);
		}
	}
	console.log(output);
}
```

![JavaScript%20146d765e7cea40679220ad5b9e744210/15._Control_Statements_For_Loops.mp4_20210324_172632.984.jpg](JavaScript%20146d765e7cea40679220ad5b9e744210/15._Control_Statements_For_Loops.mp4_20210324_172632.984.jpg)

## Fibonacci Generator

```jsx
function fibonacciGenerator (n) {
    var febArray = [0, 1];
    if (n === 0){
        febArray = [];
    }
    else if (n === 1){
        febArray = [0];
    }
    else if (n === 2){
        febArray = febArray;
    }
    else{
        for(var m = 2; m < n; m++){
            var newNum = febArray[febArray.length - 1] + febArray[febArray.length - 2];
            febArray.push(newNum);
        }
    }
    return febArray;
    }

output = fibonacciGenerator(100);
console.log(output)
```