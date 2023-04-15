# Letterboxer Documentation

# Contents

- [0.0 Foreword](#0-0-foreword)

- [1.0 Bootstrap Glossary](#1-0-bootstrap-glossary)

    - [1.1 The Sidebar](#1-1-sidebar)

    - [1.2 Cards](#1-2-cards)

- [2.0 HTML](#2-0-html)

---

## 0.0 Foreword
The primary purpose of this documentation is to provide a means of interpreting the various "helpful" Bootstrap abbreviations 
used in their classes, such as "me-md-0." What does it mean? That is for god to know and us to find out. During my time 
developing in this environment I have had to make ample use of the Bootstrap documentation and there is no possible way I 
would be able to decipher the various classes and modifiers being used if I were to take even a five minute break from coding. 
I also hope to document other things such that I don't need to leave comments on my code, because thorough documentation is 
preferable than ugly code comments explaining every little thing. I also like to include a readme.txt that slowly records my 
descent into madness as yet another QUT assessment destroys all fifteen of my brain cells. But this is a good thing, because 
from the scorched Earth rises a pheonix, and pheonixes are cool.

## 1.0 Bootstrap Glossary
  * `d-flex` *display-flex*
  * `p-3` *padding* {padding}-{size}
  * `mb-3` *margin-bottom* {property}{sides}-{size}
  * `ms-md-0` *margin-start* {property}{sides}-{breakpoint}-{size}
  * `ms-3` *margin-start* {property}{sides}-{size}
  * `me-md-0` *margin-end* {property}{sides}-{breakpoint}-{size}
  * 'me-3` *margin-end* {property}{sides}-{size}
  * `fs-3` *font-size* {property}-{size}
  * `fw-normal` *font-weight* {property}-{weight}
  * `mx-auto` *margin-left && margin-right* {property}{sides}-{size}
  * `my-auto` *margin-top && margin-bottom* {property}{sides}-{size}

## 2.0 HTML
### 2.1 Sidebar
This took a while to get right, I forced myself to try and make it work with Bootstrap
which led to some severe brain hemorrhaging. I mocked it up in plain CSS to get an idea
of what I wanted, which made me question why I was even using Bootstrap as I spent
hours shedding brain cells to get my sidebar to fill the vertical space of the viewport
which it sometimes did in Firefox but not Chrome, or vice versa, or neither at all. When
it did work, the elements of the sidebar would not be fixed, and would grow and shrink with
the size of the sidebar despite having grow and shrink values of zero. It ended up being
the y-axis margins `my-n` which I changed from auto values to fixed values. 

I then filled the sidebar with lots of primo content, real sick shit. 
