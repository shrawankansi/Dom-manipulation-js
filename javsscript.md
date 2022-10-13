# Dom Manipulation Assignment

# 1. Webiste Name: [Dev To](https://dev.to/ )

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./image/Pic1.png)

### Tasks
# code
```
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerText = "iNeuron" 

document.querySelector(".side-bar .crayons-card p").innerHTML = "I write code"
 
```

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

### Output

![Output](./image/Pic2.png)

# 2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./image/Picture_3.png)

### Fetch all the product name and store in an array
### code~
```
let empArr = [];

document.querySelectorAll(".as-imagegrid-item").forEach((ex) => 
    empArr.push(ex.innerText.replace("\nSupport", "")));

console.log(empArr)
```
### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']




# 3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./image/Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list
## code
```
let empArr = [];

document.querySelectorAll(".as-imagegrid-item").forEach((ex) => 
    empArr.push(ex.innerText.replace("\nSupport", "")));

console.log(empArr)
```
### Output

![Output](./image/Pic5.png)

# 4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./image/Pic6.png)

### Tasks

      Change the contact number
### code~
```
document.querySelector(".customer-support .service-number").innerText = "+91 77177 67744"
```
### Output

![Output](./image/Pic7.png)

# 5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./image/Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out
### code~
```
let newid = document.querySelector(".feature-column-carousel__button .cta")

newid.setAttribute("id", "checkO")
// It sets attribute, if there is no atribute it creates one.

document.getElementById("checkO").innerText = "Check Out"
```
### Output

![Output](./image/Pic9.png)

# 6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./image/Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.
### code~
```
function searchBG(){
    document.querySelector(".searchinput___zXLAR").style.backgroundColor="red";
}

document.addEventListener('mouseover',change_bg);
```
### Output

![Output](./image/Pic11.png)

# 7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./image/Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM
### code~
```
function search(text) {
	let input = document.querySelector("#top-nav-search-input");
	input.value = text;
	let btn = document.querySelector(".search-form");
	btn.submit();
}
search("Css Selector");

```
### Output

![Output](./image/Pic13.png)

# 8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./image/Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed
### code~
```
let arr = document.querySelectorAll("#SIvCob a");

[...arr].forEach((element) => {
    var array = ["தமிழ்", "ગુજરાતી", "ಕನ್ನಡ", "മലയാളം", "ਪੰਜਾਬੀ"];
    if(array.includes(element.innerText)){
        element.remove();
    }
});
```
### Output

![Output](./image/Pic15.png)

# 9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./image/Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.
### code~
```
document.querySelector(".content-width-extra-large .display-heading-1").style.fontFamily = "serif"

document.querySelector(".content-width-extra-large .display-heading-1").style.color = "#8B2E1D";
```
### Output

![Output](./image/Pic17.png)

# 10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./image/Pic18.png)

### Tasks

    Target the button and change background colour on mouseover
### code~
```
function changeBG(){
    document.querySelector(".btn-cta-big .login-btn-text").style.backgroundColor = "red";
};

document.addEventListener("click", changeBG)
```
### Output

![Output](./image/Pic19.png)

# 11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./image/Pic20.png)

### Tasks

    change the realme logo to ineuron logo
### code~
```
document.querySelector(".wrapper .gtag .icon-logo ").style.backgroundImage = "url(https://ineuron.ai/images/ineuron-logo.png)";
```
### Output

![Output](./image/Pic21.png)

# 12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./image/Pic22.png)

### Tasks

     change the background colour of the button to blue.
### code~
```
document.querySelector(".js-repos-container h2 a").style.backgroundColor = "blue";
```
### Output

![Output](./image/Pic23.png)

# 13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./image/Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.
### code~
```
document.querySelector(".fl-module ").innerHTML = "JSBOOTCAMP"
'JSBOOTCAMP'
```
### Output

![Output](./image/Pic25.png)

# 14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./image/Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px
### code~
```
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "100px";
'100px'
```
### Output

![Output](./image/Pic27.png)

# 15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./image/Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right
### code~
```
document.querySelector(".ps-title a").style.textAlign = "right";
```
### Output

![Output](./image/Pic29.png)

# 16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./image/Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”
### code~ 
```
document.querySelector(".section-title_title__VEDfK").innerHTML = "Start with Scratch"
```
### Output

![Output](./image/Pic31.png)

# 17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./image/Pic33.png)

### Tasks

     change the button text To current Date.
### code~
```
document.querySelector(".btn-container ").innerHTML = new Date();
```
### Output

![Output](./image/Pic32.png)

# 18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./image/Pic34.png)

### Tasks

    change the background colour blue to orange
### code~ 
```
document.querySelector(".p-footer").style.backgroundColor = "orange";
```

### Output

![Output](./image/Pic35.png)

# 19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./image/Pic36.png)

### Tasks

    extract the canon logo
### code~
```
document.querySelector(".logo").getAttribute("src")
```    

### Output

![Output](./image/Pic37.png)

# 20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./image/Pic38.png)

### Tasks

      Change the description colour black to orange
## code~ 
```
document.querySelector(".section-box .desc").style.color = "orange";
```      

### Output

![Output](./image/Pic39.png)
