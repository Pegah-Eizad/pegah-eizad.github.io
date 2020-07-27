---
layout: post
title: Conditional Component Rendering in React
author: Pegah Eizadkhah
date: '2020-07-24 14:35:23 +0530'
category:
        - react

summary: 
thumbnail:
---

Here are the best two ways to conditionally render Components in React's JSX
without using the ugly ```if else```. 

If you have an ```if else``` condition, use a ***ternary operator***- 
You have cookbook app and you want to render ```<Food />``` if the user is looking for
food recipes or ```<Drinks />``` if the user is looking for drink recipes.

![alt text](/assets/img/posts/jsx-ternary.png)

 note that ```isFood``` could be local component state or a prop. 

If you have an If but not an else use the ```&&``` operator-
For example you wanna display the user's favorite recipes IF they have any. 

![alt text](/assets/img/posts/jsx-and.png)

 Where favorites either comes from local state or a prop. 
 ```&&``` is the JavaScript logical "and" and will check each expression in order. 
 So in our case, it will check if the user has any favorites and if that 
 evaluates to True, it will execute what follows which is rendering 
 ```<FavoriteRecipes />``` . For rendering ```<FavoriteRecipes />```, the && operator will
 always evaluat to True as long as the component is there. 