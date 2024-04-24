---
title: hello world 
description: this is hello world markdown
date: 2024-04-17T13:45:32.509Z
draft: false
tags:
    - hello
    - world
type: default
slug: hello-world
---
{{< lead >}}
This is hello world of markdown of Congo Theme (markdown + hugo).  
(leading text)
{{< /lead >}}

<!--need two spaces at the end of the line-->
Soft line break  
Soft line break

Hard line break

Hard line break

dummy text  
Ipsum tempor lab oris sunt. Cillum fugiat eiusmod sunt magna est voluptate ipsum elit quis tempor dolore eiusmod est. Anim cupidatat adipisicing amet. Id sunt eu culpa proident id anim non ex. Elit qui ex elit sunt non veniam ex anim cupidatat aliqua mollit ipsum tempor. In quis labore ullamco excepteur ut quis nulla culpa consectetur fugiat nulla exercitation cillum. Velit ullamco sint reprehenderit nulla occaecat dolore amet occaecat eiusmod nostrud et quis amet nulla minim. Commodo elit fugiat adipisicing magna culpa velit Lorem occaecat occaecat fugiat amet aute.

**bold**

*italic*

~~strikethrough~~

`code`

```python
def hello():
    # this is code block
    print("Hello World")
```

> blockquote  
> 새옹지마니라  

1. ordered list
2. ordered list
3. ordered list

- unordered list
- unordered list
- unordered list

[link](https://www.naver.com)

![image](images/placeholder.png "this is makrdown version image (round corner)")

{{< figure src=images/placeholder.png caption="this is shortcode version image (sharp corner)" >}}

<center>
    <img src=images/placeholder.png width=100>
    <figcaption>this is html</figcaption>
</center>

<!-- this will not be rendered

you can't see this text in the browser -->

according to this paper[^1]

according to other paper[^2]

y = x^2  
y = x<sup>2</sup>

H_2O  
H<sub>2</sub>O

## Math Equation

### Inline Math Equation
this is an inline math equation. $\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$ As you can see, you can put math equation in the middle of the text.

### Block Math Equation
this is block math equation.
$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$
block math equation is centered and separated from the text.

#### Equation Alignment
$$
\begin{align*}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{align*}
$$
This is an aligned equation by '=' sign.


[^1]: footnote 1
[^2]: footnote 2

