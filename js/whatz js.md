# whatz js
[JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

Document Object Model (DOM) API, which allows you to manipulate documents.
![-w715](media/15887508895729/15887510604715.jpg)

## demo 
![-w737](media/15887508895729/15887512162934.jpg)
DOM DOM DOM !!!
code 
```js
let myImage = document.querySelector('img');

myImage.onclick = function() {
    let mySrc = myImage.getAttribute('src');
    if(mySrc === 'images/firefox-icon.png') {
      myImage.setAttribute ('src','images/firefox2.png');
    } else {
      myImage.setAttribute ('src','images/firefox-icon.png');
    }
}
```