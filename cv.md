# Dmitriy Kovalenko #
### Student RS School ###
----
### Contacts: ###
* **Telephone:** _+375297061313_
* **Git Hub:** [*My git*](https://github.com/Mihalk92)
* **Email:** [*mihalk9292@gmail.com*](https://mail.google.com/)
* **Telegram:** [Mihalk](https://t.me/Mihalk92)
---
### About me: ###

*My goal is to successfully complete my training at RSSchool in the near future. To do this, I have such qualities as: perseverance and quick learning. My hobbies are sports (football). I am currently working in a bank*
***
### Education: ###

##### Secondary education: #####
College VGPС (2012)
##### Higher education: #####
VSTU at this moment....
***
#### Code example: ####
*Create a function finalGrade, which calculates the final grade of a student depending on two parameters: a grade for the exam and a number of completed projects.*

*This function should take two arguments: exam - grade for exam (from 0 to 100); projects - number of completed projects (from 0 and above);*

*This function should return a number (final grade). There are four types of final grades:*

* *100, if a grade for the exam is more than*
* *90 or if a number of completed projects more than 10.*
* *90, if a grade for the exam is more than 75 and if a number of completed projects is minimum 5.*
* *75, if a grade for the exam is more than 50 and if a number of completed projects is minimum 2*
* *0, in other cases*

```
function finalGrade (exam, projects) {
  console.log(exam, projects);
  if (exam > 90 || projects > 10 ) {
    return 100;
} else if (exam > 75 && projects >= 5) {
   return 90;
} else if ( exam > 50 && projects >= 2) {
  return 75;
}
  else {
    return 0;
  }
}
```
***
### Programming level:  ###
*Beginner*
***
### Languages: ###
*English (A2), Russian native*