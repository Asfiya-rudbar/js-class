# js-class


// ********data type in js*********
// 1) Primitive Datatype - 7types

// i)String- "Asfiya"
// let myname = "Asfiya";
// console.log(myname);
// console.log(typeof myname);

// ii) Number - 2^53
// let num = 463;
// console.log(num);
// console.log(typeof num);


// iii) BigInt - 
// let bigIntValue = 56n;
// console.log(bigIntValue);
// console.log(typeof bigIntValue);



// iv) null - ""   null is object type typetype
// const response = null;
// console.log(typeof response);


// v) undefined

// let myage ;
// console.log( myage);

// // vi) Symbol - for uniqueness
// let id = Symbol('123');
// let anotherId = Symbol('123');
// console.log(id == anotherId);


// vii) boolean - true/false 
// const isLoggedIn = true;
// console.log(isLoggedIn);
// console.log(typeof isLoggedIn);


// 2) Non-Primitive Datatype
// i)Array
// ii) Object
// iii) Function




// **************Type Conversion in js**************

// *****convert string in number****
//  let myNum = "20";
//  console.log(typeof myNum);
//  let myNewNum = Number(myNum);
//  console.log(typeof myNewNum);
//  console.log(myNewNum);

//  let myValue = null;
//  let myNewValue = BigInt(myValue);
//  console.log(typeof myNewValue);
//  error

//   let myValue = null;
//  let myNewValue = String(myValue);
//  console.log(typeof myNewValue);


// ********Datatype Comparison in js*********
console.log("1"+3+7);
console.log(1+3+"7");



// console.log(null<0);
// console.log(null>0);
// console.log(null>=0);
// console.log(null<=0);
// console.log(null==0);

// console.log(null== undefined);
// console.log(typeof null);



// let myName = "Asfiya";
// let myNewName = "Asfiya Rudbar";
// myName = myNewName ;
// console.log(myName);

// let myArray = ["ifra" , "Asfiya", "rudbar"];
// console.log(myArray);
// let myNewArray = myArray.pop();
// console.log(myArray);


// let myName = "Asfiya";
// let myNewName = "Asfiya Rudbar";
// console.log(myName[0]);
// console.log(myName.__proto__);
// console.log(myName);


// // kis index pr kon sa character h
// console.log(myName.charAt(3)); 

// //  kon sa character kis index pr h 
// console.log(myName.charAt(r));



// console.log(myName.substring(0,6));


// *************Number in js*************
// let myNum = 20;
// console.log(myNum.toString().length);
// console.log(myNum.toFixed(2));
// console.log(myNum.toPrecision(3));

// let mynum = 20.34;
// console.log(mynum.toString().length);
// console.log(mynum.toFixed(2));
// console.log(mynum.toPrecision(3));


// ************Maths in js*********
// console.log(math.abs(4));
// console.log(math.floor(4.7));
// console.log(Math.floor(math.random()*10)+1);

// const min = 1;
// const max =10;
// console.log(Math.floor(Math.random(max-min)*10)+1);
// console.log(Math.random());

// ******dice roll*****
// console.log(Math.floor(Math.random()*6)+1);


// // ******Change background color******

// console.log(`rgb(${Math.random()*255})`);





function changeColor() {
  document.body.style.backgroundColor = `rgb(${Math.floor(
    Math.random() * 255
  )},${Math.floor(Math.random() * 255)},${Math.floor(Math.random() * 255)})`;
}

