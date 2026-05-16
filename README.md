// Post increment (value++)
var a = 5;
a++

var b=a++;
console.log("post increment")
console.log(b)
console.log(a)
//pre increment
var a = 3;
++a
var b=++a;
console.log("pre increment")
console.log(b)
console.log(a)

var a=2;
a++
var b=a++;
var c=++a;
console.log("post-increment" +","+ "pre-increment")
console.log(b)
console.log(c)
console.log(a)

//post decrement
var p = 3;
p--
var q = p--;
console.log("post decrement")
console.log(q)
console.log(p)

//pre decrement
var p = 7;
--p
var q=--p;
console.log("pre decrement")
console.log(q)
console.log(p)

var p=5;
p--
var q=p--;
var r=--p;
console.log("post decrement"+","+"pre decrement")
console.log(q)
console.log(r)
console.log(p)

//Adding post,pre increments.
var g=5;
var h=g++ + ++g;
console.log("Adding post,pre increments")
console.log(h)//6+6 = 12
console.log(g)

//Adding post,pre decrements
var j=6;
var k=j-- + --j;
console.log("Adding post,pre decrements")
console.log(k)
console.log(j)

//Adding multiple ways
var g=2;
var h=--g + g-- + g++
console.log(h)



// logical - (&&,||,!)

//And operator(&&)
let age = 23;
console.log(age>25)
console.log(age<25)
console.log(age<25 && age>25)//F&&T=F
console.log(age>22 && age<22)//T&&F=F
console.log(age<25 && age>20)//T&&T=T
console.log(age<20 && age>25)//F&&F=F

//OR operator(||)
let a=10;
let b=20;
console.log(a>b || a<b)//F||T=T
console.log(a>b || b<a)//F||F=F
console.log(b>a || b<a)//T||F=T
console.log(b>a || a<b)//T||T=T

//NOT operator(!)
let pavan=true;
console.log(!pavan)
console.log(pavan)

let marks = 17;
let hasPassed = true;

if (marks >= 18 || hasPassed) {
    console.log("Allowed");
} else {
    console.log("Not Allowed");
}

