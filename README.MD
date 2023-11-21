Javascript important Commands /Methods -->
<!--->Array Filter method   21/11/2023<--->
Array filter takes in array and filter array that is return array itself ,without changing original array 
*/
const ages=[32,22,34];
const result =ages.filter((age)=>age>30);
console.log (result);
//alternate way of writing same code is -->
const result1=ages.filter(agefilter); 
/*
Here this recieves either 1 or 0 ,for 1 it stores in array and for others it reject ,hence 
*/
function agefilter(age){
    return age >=33 ;
    /*
    <!--> This function returns true or false depending on the condition check and return  1 or 0
    */
}
console.log(result1);
<!--> Array.From method   <--->

<!--> document.getElementsByClassName('dhdjhjd')<-->
This targets only class name of all html element and returns array of all html element .
<!--> document.getElementsByTagName('dhdjhjd')<-->
This targets only tag  name of all html element and returns array of all html element .
Note :Tag mean <p> or <a> or so on .
<!--> document.getElementsById('dhdjhjd')<-->
Id is always unique for each element 
This targets only id  of all html element and returns array of all html element .#Unique 
Link for understanding this is  
https://youtu.be/0pqLp51w7dw?si=P85q_Rb0Qs9J2lRX







