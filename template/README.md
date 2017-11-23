# Slide Template

main content

<left>test</left>

---

# slide 1

content

===

# slide 1-1

content

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

---

# Configuration

[reveal.js :: configuration](https://github.com/hakimel/reveal.js/#configuration)
