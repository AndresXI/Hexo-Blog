---
title: BEM Architecture in CSS
date: 2018-11-10 17:38:54
tags:
---

# BEM Notation 

When you first start to lean CSS, how you organize your code is usually not one of your main priorites, but as you get more comfotable with CSS and start working on big projects you will need a paradigm to orgazie your styles. There are plenty of paradigms out there but one of my favorites is the BEM (Block, Elements and Modifiers) notation. Is it a very intuitive methodoly that keeps your code organized. Ok so how does it work? 

## The Basics 
In all its glory, the Block, Elements, and Modifiers notation is just a naming convention. Say for example when you create a form component that has an image, a description, and a button, the block would be named .form, it must be meaningful on its own. Then any sections whithin the form block would be the elemets, in our exempale that would be the description, image, and button. We name it by using two undercores __elemment. Finally, when you want to change the appeareace or behavior of an element you use a modifier and connect them with two dashses, putting it all together it will look like this ```
 .form__button--dark 
 ```

 ![BEM](https://github.com/AndresXI/Hexo-Blog/blob/master/form.png)