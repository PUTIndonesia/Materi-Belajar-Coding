# CODING MUM

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Presentation][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------------:|:--------------:|:-----------------:|

---

### LESSON 03: WEBSITE STRUCTURE

---

### Objectives
1. Peserta mengerti struktur website dibentuk dari **HTML** `div`, dibantu **CSS** `float`.
2. Peserta mampu membuat baris dan kolom menggunakan **HTML** `div` dan **CSS** `float`.

---

### Material

#### 1. HTML dan CSS 1 Kolom
* HTML `index.html`
  ```html
  <div class="parent">
    Ini div 1 kolom
  </div>
  ```
* CSS `style.css`
  ```css
  .parent {
    background-color: #ff0000;
    height: 200px;
    width: 100%;
  }
  ```

#### 2. HTML dan CSS 2 Kolom
* HTML `index.html`
  ```html
  <div class="parent">
      <div class="child1">Ini section 1</div>
      <div class="child2">Ini section 2</div>
  </div>
  ```
* CSS `style.css`
  ```css
  .parent {
      background-color: aqua;
  }
  .child1 {
      background-color: brown;
      float: left;
      width: 20%;
  }
  .child2 {
      background-color: cornflowerblue;
      float: right;
      width: 80%;
  }
  ```

#### 3. HTML dan CSS 3 Kolom
* HTML `index.html`
  ```html
  <div class="parent2">
      <div class="childa">Ini section 1</div>
      <div class="childb">Ini section 2</div>
      <div class="childc">Ini section 3</div>
  </div>
  ```
* CSS `style.css`
  ```css
  .parent2 {
      background-color: blueviolet;
      margin-top: 50px;
  }
  .childa {
      background-color: bisque;
      float: left;
      width: 33%;
  }
  .childb {
      background-color: chocolate;
      float: left;
      width: 34%;
  }
  .childc {
      background-color: cadetblue;
      float: left;
      width: 33%;
  }
  ```

---

### File
[Download file for this lesson: lesson-03.zip](files/lesson-03.zip)

---

### Latihan
1. Peserta membuat 3 dan 4 kolom bagian website menggunakan **HTML** `<div>` dan **CSS** `float`.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 03** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 03** ini?

---

### Referensi

---

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Presentation][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------------:|:--------------:|:-----------------:|

[0]: README.md "Home"
[1]: lesson-01.md "Website Development Introduction"
[2]: lesson-02.md "HTML and CSS Basic"
[3]: lesson-03.md "Website Structure"
[4]: lesson-04.md "Framework Introduction"
[5]: lesson-05.md "Framework (Continued))"
[6]: lesson-06.md "Personal Project"
[7]: lesson-07.md "Domain, Hosting dan GitHub"
[8]: lesson-08.md "Presentation"
