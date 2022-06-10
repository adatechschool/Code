function askName () {
let person = prompt ("Name?")
var hiName = ("&#9995 bonjour " + person)
document.body.innerHTML += '<h2>'+ hiName +'</h2>' ; }

function askAge () {
let birthYear = prompt ("Birthyear?")
var dateNow = new Date().getFullYear();
let age = (dateNow - birthYear)
let response = ("Vous avez " + age + " ans")
document.body.innerHTML += '<h3>'+ response +'</h3>' ; }

askName ();
askAge();
