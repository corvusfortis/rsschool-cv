## Denis Avdizba

***

###  Contact info

***

**Phone number:** +79188540327  
**E-mail:** denisavdizba@mail.ru  
**Discord:** Corvian (GMT+3)#8349  

### About me:

***

Graduate student from Sukhum, Abkhazia.  
Moved to Taganrog, Russia, to study IT at ETA SFEDU.  
My goal is to learn frontend web development and I spend quite some of my free time studying.   
I worked as a teacher in SmartLab children school of robotics and programming. I was teaching basic HTML and CSS.  
I am always up to learn new things, open-minded and determined to accomplish all my goals. I always enjoy new acquiantances and like to teach people new skills.  

### My skills

***

Front-end

* HTML
* CSS
* Basic JavaScript
* Bootstrap
* SASS
* React (in progress)

Infrastructure

* Git

IDE

* VSCode

### Code example

***

**Human Readable Time**

*This function converts given number of seconds to HH:mm:ss format.*

```
function humanReadable (seconds) {
  let hours = Math.floor(seconds/3600);
  let minutes = Math.floor(seconds/60);
  while(seconds >=60){
    seconds -= 60;
  }
  while (minutes >= 60){
    minutes -= 60;
  }
  hours > 9 ? hours = String(hours) : hours = "0" + String(hours);
  minutes > 9 ? minutes = String(minutes) : minutes = "0" + String(minutes);
  seconds > 9 ? seconds = String(seconds) : seconds = "0" + String(seconds);
  return `${hours}`+":"+`${minutes}`+":"+`${seconds}`;
}
```


### My projects

***

 [Javascript ToDo App (WIP)](https://github.com/corvusfortis/todo_js)

### Education

***

- **University:**  ETA SFEDU, Informational technologies and communication systems master
- **Complited Courses:**
    - **Stepik:** Javascript for beginners
    - **FreeCodeCamp:** Responsive Web Design, Javascript Algorithms and Data Structures
    

### Languages

***


**Russian**: Native speaker  
**English**: B1 (Intermediate)