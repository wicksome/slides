# Slide Template

md file: https://github.com/wicksome/slides/blob/master/template/README.md

reveal.js <!-- .element: style="text-align: right;" -->  

---

# slide 1

content

===

# slide 1-1

content

---

# Text align: left
<!-- .slide: style="text-align: left;" -->  

content

```
<!-- .slide: style="text-align: left;"> -->
```

===

# Text align: right 
<!-- .slide: style="text-align: right;" -->  

content

```
<!-- .slide: style="text-align: right;" -->
```

===

# Text 

right <!-- .element style="text-align: right;" -->

content

left <!-- .element style="text-align: left;" -->

---

# Image resizing

height: 120px

![](https://pilbox.themuse.com/imageNone?url=https%3A%2F%2Fassets.themuse.com%2Fuploaded%2Fattachments%2F14431%3Fv%3DNone&h=367)<!-- .element height="120px" -->

```
![image](image-url)<!-- .element height="120px" -->
```

===

# Image resizing

width, height: 50%

![](https://pilbox.themuse.com/imageNone?url=https%3A%2F%2Fassets.themuse.com%2Fuploaded%2Fattachments%2F14431%3Fv%3DNone&h=367)<!-- .element height="50%" width="50%" -->

```
![image](image-url)<!-- .element height="50%" width="50%" -->
```

---

# Background Color
<!-- .slide: data-background="#ffeeee" -->

```
<!-- .slide: data-background="#ffeeee" -->
```

===

# Background Image
<!-- .slide: data-background="http://freedesignfile.com/upload/2016/12/Beautiful-pink-flowers-HD-picture.jpg" -->

```
<!-- .slide: data-background="image-url" -->
```

---

# Fragment

- Item 1 <!-- .element: class="fragment" data-fragment-index="2" -->
- Item 2 <!-- .element: class="fragment" data-fragment-index="1" -->

```
- Item 1 <!-- .element: class="fragment" data-fragment-index="2" -->
- Item 2 <!-- .element: class="fragment" data-fragment-index="1" -->
```

---

## Custom CSS
<!-- .slide: class="custom-background" -->

css 파일 생성하고, index.html 추가

```html
<link rel="stylesheet" href="./custom.css">
```

```css
.custom-background {
    background-color: #ffeeee;
}
```

===

## Custom logo

배경설정 안했을 경우에만 적용

```css
body {
    background-image: url(./logo.png);
    background-size: 10%;
    background-repeat: no-repeat;
    background-position: 3% 96%;
}
```

---

# Configuration

[reveal.js :: configuration](https://github.com/hakimel/reveal.js/#configuration)
