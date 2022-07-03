# java_async-await

const getData = async() => {
    var y = await "javaScript";
    console.log(y);
}
 
console.log(1);
getData();
console.log(2);


output
1
2
javaScript
