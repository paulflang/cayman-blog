---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit cayman-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>

<figure>
  <img border="0" src="https://media-exp1.licdn.com/dms/image/C4D03AQGkNgGMjAGfnA/profile-displayphoto-shrink_200_200/0?e=1595462400&v=beta&t=XDOZ3cHMXgG4ICh2haW2T7oEU8o884oYzal2cjPbQ2I" align="left" alt="Paul Lang"/>
  <figcaption float="left">Paul Lang</figcaption>
</figure>

Hi,

I am Paul, a PhD student working on mathematical cell cycle models based on multiplexed imaging data. Trying to make the transition from an experimental biologist to a computational systems biologist I regularly come across several fascinating new concepts. To remind my future self of the key ideas of these concepts, I created this glossary. If you are anything like my envisioned future self, you may find this glossary useful, too. However, please take the content of this blog with a grain of salt. Some of the content may be oversimplified or not even correct. If you find mistakes or want to contribute to this glossary, please raise an issue or create a pull request on the [sysbio-glossary GitHub repository](https://github.com/paulflang/sysbio-glossary).
