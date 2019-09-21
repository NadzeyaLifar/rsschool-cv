# Hello this is my cv

1. **First Name, Last Name:**	Nadzeya Lifar
2. **Contact Info:**
	* e-mail: nadik.lifar@gmail.com
    * tel: +375(29)110-40-10
3. **Summary:**	Hard-working web developer with a flair for creating elegant solutions in the least amount of time. Developed an ecommerce webapp, customer web portal, documentary launch website, and donations webapp for a local charity. Passionate about software architecture and cloud computing. Regular attendee of web developer meetups and hackathons.
4. **Skills:**	HTML5, CSS, Javascript, Git
5. **Code examples:** ```(function () {

    'use strict'; 

 (function showUserInfo () {

 let firstName = prompt('Введите имя');
 let str = firstName.trim();
 
 let lastName = prompt('Введите фамилию');
 let str1 = lastName.trim();
 
 while (firstName == '' || firstName == null) {
     firstName = prompt ('Введите Имя еще раз, данные не корректны');
 }
 
 while (lastName == '' || lastName == null) {
     lastName = prompt ('Введите Фамилию еще раз, данные не корректны');
 }
 let gender = prompt('Введите Ваш пол М или Ж');
 
 while (!(gender.toUpperCase() == 'М' || gender.toUpperCase() == 'Ж')) {
     gender = prompt ('Введите Введите пол еще раз, данные не корректны'); 
 }
 
 let age = +prompt('Введите Ваш возраст в годах');//возраст преобразуем в число
 
 while (typeof (age) != 'number' || age == null || age <= 0) {
     age = +prompt ('Введите Возраст еще раз, данные не корректны');
 }

 function checkRetired () {
 if ((gender.toUpperCase() == 'M' && age >= 63) || (gender.toUpperCase() == 'Ж' && age >=58)) {
     return 'Да';
 }
     else {
     return 'Нет';
     }
    }

 alert ('Полное имя:' + ' ' + str + ' ' + str1 + '\n'
         + 'Пол:' + ' ' + gender.toUpperCase() + '\n'
         + 'На пенсии:' + ' ' + checkRetired());

    })()
 
 }()); ```
 6. **Experience:**	"Website development using html and css" courses at IT-Academy,
"JavaScript web application development" courses at IT-Academy,
interactive courses at HTMLAcademy,
*[My SITE](https://noanails-e41c2.firebaseapp.com)*
7. **Education:** "Website development using html and css" courses at IT-Academy,
"JavaScript web application development" courses at IT-Academy,
interactive courses at HTMLAcademy
8. **English:**	Upper-intermediate level
