# Nastya Kazakova
## Personal Data
*email* nasty.nagato@gmail.com
*phone* +375295760852
*github* [NastyaKazakovaa](https://github.com/NastyaKazakovaa)
## About me
Junior frontend developer
## Skills
* HTML/CSS
* JS
* React
* jQuery
## Code examples
```  function getDistanceBetweenSlideImages(el1, el2) {
    el1rect = el1.getBoundingClientRect();
    el2rect = el2.getBoundingClientRect();
    el1x = el1rect.left + el1rect.width / 2;
    el1y = el1rect.top + el1rect.height / 2;
    el2x = el2rect.left + el2rect.width / 2;
    el2y = el2rect.top + el2rect.height / 2;
    // calculate the distance using the Pythagorean Theorem (a^2 + b^2 = c^2)
    let distanceSquared = Math.pow(el1x - el2x, 2) + Math.pow(el1y - el2y, 2);
    return Math.sqrt(distanceSquared);
  }
  function setLineWidthBetweenSlideImages() {
    document.documentElement.style.setProperty(
      "--line-distance",
      getDistanceBetweenSlideImages(img1, img2) + "px"
    );
  }
  ```
  ## experience
  * software engineer at ZOOMOS,
  * frontend development courses MYFREEDOM
  ## education
  teacher of physics and computer science at BSPU 
  ## level of english
  B1(Intermediate)
