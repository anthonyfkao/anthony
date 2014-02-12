anthony
=======
First, declare an array named myArray
Great! Now populate myArray with two strings.
Put your full name in the first string, and your Skype handle in the second.
Next, declare a function named cutName. It should take a string as an argument.
cutName should return an array by breaking up the input string into individual words. For example "Brendan Eich" should be returned as ["Brendan", "Eich"]
Make a new empty object literal named myData
Add three key-value pairs to myData, by following these guidelines
fullName : call cutName on the name string stored in myArray
skype : refer to your Skype handle in myArray
github : If you have a github handle, enter it as a string. If not, set this to null

var myArray = ["Anthony Kao","anthonyfkao"];
function cutName() { 
  var name=myArray[0];
  return [name.split(" ")];
}
var myData={'fullName':cutName(),'skype':myArray[1],'github':'anthonyfkao'};
