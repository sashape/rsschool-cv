# Aleksandr Penskoy
## Junior Fronted Developer
----------
#### Contact information:
Phone: [+90(543)-168-43-99](tel:+905431684399)  
E-mail: sashape89@gmail.com  
Telegram: @sashape  
[LinkedIn](https://www.linkedin.com/in/aleksandr-penskoy-3b7416234/)


----------
#### About me
Greetings, fellow humans! Please allow me to present my resume, a collection of my professional accomplishments and skills. As an experienced developer, I have spent many moons honing my craft in PHP backend and jQuery frontend development, and more recently I've been delving into the world of Vue development as well. To further my quest for programming mastery, I've even enrolled in the esteemed rsschool to sharpen my JS skills and become a true full-stack wizard.

But enough about me, let me tell you about my personal life! When I'm not busy coding, I enjoy spending time with my lovely wife and our beloved hairless dog. Yes, you heard that right, a hairless dog! I guess you could say that I have a penchant for unique and unconventional things, much like my coding style. In fact, my coding is so clean and efficient that it makes my computer run so fast that it's practically flying! Or maybe that's just because I installed a new SSD... well, I like to think it's my code!

#### My skills
- javascript
- html, css
- php
- mysql
- git
- linux
- docker
- nginx


#### Code example
Simple code fragment from Vue project. This is a method of component which can switching video on click.
```javascript
touchend(e) {
  // stopping timer
  clearInterval(this.touchTimer);
  // If greater than 5s, then continue playing
  if(this.touchTime > 5) {
    this.playButton();
  // If not we search for which side (left or right) of screen user clicked
  } else if(Math.round(window.innerWidth / 2) < e.changedTouches[0].clientX) {
      this.nextVideo();
    } else {
      this.prevVideo();
    }
  }
}
```
#### Learning
2006 - 2010: Volzhky Politech College "IT specialist"  
2010: Offline course "Building Websites"  
2011: php.net learning documentation by myself  
2015: Styding book from learn.javascript.ru  
2023: rsschool JS / FRONT-END course stage #1  

#### Working experience
2011-2019 - freelance, building websites on modx and wordpress  
2019 - full-stack developer at eastclinic.ru  

#### Languages
Russian - native  
English - B1 intermediate by  
![english skill](/images/english.png)