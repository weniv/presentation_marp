---
# theme를 hojun으로 바꾸면 커스텀 테마 적용
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
marp: true
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

![bg left:40% 80%](https://marp.app/assets/marp.svg)

# **Marp**

Markdown Presentation Ecosystem

https://marp.app/

---

# How to write slides

Split pages by horizontal ruler (`---`). It's very simple! :satisfied:

```markdown
# Slide 1

foobar

---

# Slide 2

foobar
```

---

<!-- 백그라운드 이미지 있어서 덮어씀 -->
<!-- backgroundColor: orange -->
<!-- color: white -->
<!-- color: blue -->
<!-- 헤더에 logo 가능 -->
<!-- header: 'hello, world!' -->

# hello, world!

- paginate Show page number on the slide if you set true.
- header Specify the content of slide header.
- footer Specify the content of slide footer.
- class Specify HTML class of slide’s <section> element.
- backgroundColor Setting background-color style of slide.
- backgroundImage Setting background-image style of slide.
- backgroundPosition Setting background-position style of slide.
- backgroundRepeat Setting background-repeat style of slide.
- backgroundSize Setting background-size style of slide.
- color Setting color style of slide.
  ![width:200px](image.jpg) <!-- Setting width to 200px -->
  ![height:30cm](image.jpg) <!-- Setting height to 300px -->
  ![width:200px height:30cm](image.jpg) <!-- Setting both lengths -->

---

<!-- header: '![width:100px](assets/weniv_logo.png)' -->

![bg](https://fakeimg.pl/800x600/0288d1/fff/?text=A)
![bg](https://fakeimg.pl/800x600/02669d/fff/?text=B)
![bg](https://fakeimg.pl/800x600/67b8e3/fff/?text=C)

---

![bg left:33%](https://picsum.photos/720?image=27)

---

<!-- 중앙 정렬 -->

<!-- _class: lead -->

hello world

---

<!-- _class: lead -->

|        2020년        |        2021년        |             2022년              | 2022년                 |
| :------------------: | :------------------: | :-----------------------------: | ---------------------- |
| ![](images/2020.png) | ![](images/2021.jpg) | ![width:140px](images/2022.png) | ![](images/2022_1.png) |

---

<!-- _class: lead -->

![width:600px](images/cycle.png)

<style>
    p {
        font-size: 20px;
    }
</style>

출처 : https://aptonova.wordpress.com/2014/11/01/how-to-escape-from-the-start-up-valley-of-death/

---
