# index
let multiply =function(x,y) {
    console.log(x*y);
}

let multiplyByTwo =multiply.bind(this,2);
multiplyByTwo(6);

let multiplyByThree =multiply.bind(this,3);
multiplyByThree(7);
