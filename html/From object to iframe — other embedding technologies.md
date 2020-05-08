# 10 - From object to iframe — other embedding technologies

## active learning
embed the Youtube Video~
<iframe width="560" height="315" src="https://www.youtube.com/embed/t4naLFSlBpQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
code below:
```
<iframe width="560" height="315" src="https://www.youtube.com/embed/t4naLFSlBpQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
1. First, go to Youtube and find a video you like.
2. Below the video, you'll find a Share button — select this to display the sharing options.
3. Select the Embed button and you'll be given some `<iframe> `code — copy this.
4. Insert it into the Input box below, and see what the result is in the Output.

## Iframes in detail
`<iframe>` elements are designed to allow you to embed other web documents into the current document.

```
<iframe src="https://developer.mozilla.org/en-US/docs/Glossary"
        width="100%" height="500" frameborder="0"
        allowfullscreen sandbox>
  <p> 
    <a href="https://developer.mozilla.org/en-US/docs/Glossary">
       Fallback link for browsers that don't support iframes
    </a>
  </p>
</iframe>
```
![-w751](https://i.loli.net/2020/05/08/5rObP1F982oMQiH.jpg)
****
