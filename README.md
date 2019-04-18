# Portfolio Website Ver2
The second version of my portfolio website

## Table of Contents
1. <b>[Work](https://github.com/cmdlhz/portfolio_website_ver2#1-work)</b>
2. <b>[Writings](https://github.com/cmdlhz/portfolio_website_ver2#2-writings)</b>
3. <b>[About](https://github.com/cmdlhz/portfolio_website_ver2#3-about)</b>
4. <b>[Account](https://github.com/cmdlhz/portfolio_website_ver2#4-account)</b>
5. <b>[Main Page](https://github.com/cmdlhz/portfolio_website_ver2#5-account)</b>
6. <b>[Navigation](https://github.com/cmdlhz/portfolio_website_ver2#6-navigation)</b>
7. <b>[General](https://github.com/cmdlhz/portfolio_website_ver2#7-general)</b>
8. <b>[Useful Info](https://github.com/cmdlhz/portfolio_website_ver2#8-useful-info)</b>
    - 8.1. [GitHub README Markdown : Useful Techniques](https://github.com/cmdlhz/portfolio_website_ver2#81-github-markdown--useful-techniques)
9. <b>[References](https://github.com/cmdlhz/portfolio_website_ver2#9-references)</b>
    - 9.1. [Front-end](https://github.com/cmdlhz/portfolio_website_ver2#91-front-end)
    - 9.2. [Back-end](https://github.com/cmdlhz/portfolio_website_ver2#92-back-end)
    - 9.3. [DB](https://github.com/cmdlhz/portfolio_website_ver2#93-db)
    - 9.4. [Etc](https://github.com/cmdlhz/portfolio_website_ver2#94-etc)
    - 9.5. [Inspirations](https://github.com/cmdlhz/portfolio_website_ver2#95-inspirations)
10. <b>[Built With](https://github.com/cmdlhz/portfolio_website_ver2#10-built-with)</b>
11. <b>[Blog Posts](https://github.com/cmdlhz/portfolio_website_ver2#11-blog-posts)</b>
12. <b>[Coming Up](https://github.com/cmdlhz/portfolio_website_ver2#12-coming-up)</b>
13. <b>[Contributing](https://github.com/cmdlhz/portfolio_website_ver2#13-contributing)</b>
14. <b>[License](https://github.com/cmdlhz/portfolio_website_ver2#14-license)</b>
- - -

# 1. Work 
- - -

# 2. Writings 
- - -

# 3. About 
- - -

# 4. Account 
## 4.1. Sign Up Page

## 4.2. Log In Page

## 4.3. Account Page
- - -

# 5. Main Page
- - -

# 6. Navigation 
## 6.1. Header
### 6.1.1. ARIA 
[Accessible Rich Internet Applications (ARIA)](https://www.w3.org/TR/wai-aria-1.1/) is a set of attributes that define ways to make web content and web applications (especially those developed with JavaScript) more accessible to people with disabilities.
- Adding `aria-haspopup="true"` to the parent of the dropdown menu to indicates an alternative state.
- `aria-expanded="false"` & `aria-expanded="true"` shows that whether the alternative state is expanded or not.
- Including `aria-label="submenu"` on the actual dropdown menu itself shows that it's a submenu.


## 6.2. Footer
- - -

# 7. General 
## 7.1. Environment
"The default build of vue-server-renderer assumes a *Node.js* environment, which makes it unusable in alternative JavaScript environments such as [PHP V8Js](https://github.com/phpv8/v8js) or [Oracle Nashorn](https://docs.oracle.com/javase/8/docs/technotes/guides/scripting/nashorn/)." ([Vue SSR Guide](https://ssr.vuejs.org/guide/non-node.html))
- Because I'm using Python/Django in the backend, there is no need for me to use [NuxtJS](https://nuxtjs.org/).

- - -

# 8. Useful Info
## 8.1. GitHub README Markdown : Useful Techniques 
Please check out [this markdown](https://github.com/cmdlhz/SaferTrip_JL#61-github-markdown--useful-techniques).
- - -

# 9. References 
## 9.1. Front-end
### Overall
* <b>Testing</b>
    - [HTML-CSS-JS](https://html-css-js.com/): An online tool collection of HTML, CSS, JS
    - GreenSock
        + [GreenSock Ease Visualizer](https://greensock.com/ease-visualizer): `Power 0-4`, `Back`, `Elastic`, `Bounce`, `Rough`, `SlowMo`, `Stepped`, `Circ`, `Expo`, `Sine`
    - [Regex 101](https://regex101.com/): a regular expression debugger 
* <b>Tutorials</b>
    - GreenSock
        + [GreenSock for Beginners](https://bit.ly/2IBc8la) on YouTube by [Petr Tichy](https://twitter.com/ihatetomatoes)
    - ScrollMagic
        + [ScrollMagic for Beginners](https://bit.ly/2IBc8la) on YouTube by [Petr Tichy](https://twitter.com/ihatetomatoes)

### CSS
* <b>Testing</b>
    - [Cubic-bezier](http://cubic-bezier.com): A transition effect with variable speed from start to end
    - [Color Picker](https://www.w3schools.com/colors/colors_picker.asp): Comparing similar colors
* <b>Collections</b>
    - [30 Seconds of CSS](https://30-seconds.github.io/30-seconds-of-css/): A curated collection of useful CSS snippets
* <b>Tutorials</b>
    - [Flexbox Froggy](https://flexboxfroggy.com/): A game for learning CSS flexbox
    - [Grid Garden](http://cssgridgarden.com/): A game for learning CSS grid layout
    - [CSS Animation Tutorial Series](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iGYgmEd2dm3zAKzyCGDtM5) by [Net Ninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg)
* <b>Blogs</b>
    - [Solved with CSS! Dropdown Menus](https://css-tricks.com/solved-with-css-dropdown-menus/)

### JS
* <b>Tutorials</b>
    - [The Modern JavaScript Tutorial](https://javascript.info/)
        1) An Introduction
        2) JavaScript Fundamentals
        3) Code Quality
        4) Objects: The Basics
        5) Data Types
        6) Advanced Working with Functions
        7) Object Properties Configuration
        8) Prototypes, Inheritance
        9) Classes
        10) Error Handling
        11) Promises, Async/Await
        12) Generators, Advanced Iteration
        13) Modules

* <b>Collections</b>
    - [ES 6: New Features: Overview & Comparison](http://es6-features.org/#Constants)
* <b>Blog Posts</b>
    - [JavaScript ES2015 Classes and Prototype Inheritance](https://www.accelebrate.com/blog/javascript-es6-classes-and-prototype-inheritance-part-1-of-2/)
* <b>Theories</b>
    - [Details of the object model](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Details_of_the_Object_Model) : `Class`-based vs. `prototype`-based languages

### Vue
* <b>Collections</b>
    - [Awesome Vue](https://github.com/vuejs/awesome-vue) 
* <b>Blog Posts</b>
    - [React vs. Vue (vs. Angular)](https://medium.com/fundbox-engineering/react-vs-vue-vs-angular-163f1ae7be56) : Comparisons in "*Learning Curve*", "*Code Style*", "*Single File Components*", "*Performance*", "*Flexibility*", "*Tooling*", "*Mobile*", "*Community*", "*Maturity*", "*Support*", and "*Hiring Talent*"
* <b>Tips</b>
    - [How to use various themes of icons from Google's Material Design in Vuetify](https://github.com/vuetifyjs/vuetify/issues/4164)

### Etc..
* <b>Collections</b>
    - [Giphy](https://giphy.com/)
    - [Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)
    - [Google Fonts : Korean](https://googlefonts.github.io/korean/)
* <b>Blog Posts</b>
    - [How I landed a full stack developer job without a tech degree or work experience](http://bit.ly/2D06sl5) by [Charlie Jeppsson](https://github.com/charliejeppsson)
* <b>Plugins</b>
    - [New Moon](https://taniarascia.github.io/new-moon/) : the optimized dark theme including syntax highlighting for web development 

## 9.2. Back-end
* <b>NuxtJS</b>
    - [Vue SSR Guide](https://ssr.vuejs.org) by [VueJS](https://vuejs.org)
    - [The Complete Nuxt Guide](https://medium.com/@onlykiosk/the-complete-nuxt-guide-940751e1a6a5) by [OnlyKiosk Dev Tech](https://medium.com/@onlykiosk)

## 9.3. DB
* <b>Visualization</b>
    - [DrawSQL](https://drawsql.app/) : Create, visualize and collaborate on database entity relationship diagrams

## 9.4. Etc
* <b>Online Code Editor</b>
    - [StackBlitz](https://stackblitz.com/)
    - [Code SandBox](https://codesandbox.io/)
* <b>Etc</b>
    - [Post Image](https://postimages.org/) : Get permanent links for images

## 9.5. Inspirations
* <b>Interactive Experience</b>
    - [Website Awwwards](https://www.awwwards.com/) : scores based on design, usability, creativity, content, and mobile
    - [Form Follows Function](http://fff.cmiscm.com/#!/main)
    - Bunts Spenden @ [website](http://buntspenden.bleech.de/en/)
        + [awwwards submission](https://www.awwwards.com/sites/buntspenden)
    - 12 Dishes @ [website](http://12dishes.com/)
        + [awwwards winner](https://www.awwwards.com/sites/around-the-world-in-12-dishes) of Jan 27, 2016.
        + [youtube explanation](https://youtu.be/Wu7OHhdqT0c)
    - [Fly Acts - Multi-channel App](https://www.flyacts.com/multi-channel-app/)

* <b>Portfolio Website</b>
    - [Ji-hoon Suh](https://jihoonsuh.com/)
    - [Jeremiah Shaw](http://www.jermshaw.com/)
    - [Derek Mei](https://www.derekmei.com/)

* <b>Programming Work</b>
    - [Tania Rascia](https://www.taniarascia.com/)
    - [José Manuel Pérez](https://jmperezperez.com/projects/)
- - -

# 10. Built With
* <b>Front End</b>
    - HTML
    - CSS
        + [Sass](https://sass-lang.com/)
    - JavaScript
        + [GreenSock Animation Platform (GSAP)](https://greensock.com/gsap) : Professional-grade javascript animation for the modern web
        + [ScrollMagic](http://scrollmagic.io/) : Javascript library for magical scroll interactions
        + [AnimeJS](https://animejs.com/):  a lightweight JavaScript animation library
        + [HeadroomJS](https://wicky.nillia.ms/headroom.js/) : A JS widget that allows you to react to the user's scroll
        + [SweetAlert2](https://sweetalert2.github.io/) : A beautiful, responsive, customizable replacement for JavaScript's popup boxes
        + [PrismJS](https://prismjs.com/) : a lightweight, extensible syntax highlighter
    - [Vue](https://vuejs.org/)
        + [Vuetify](https://vuetifyjs.com/en/) : a material component framework for Vue apps
        + [VeeValidate](https://baianat.github.io/vee-validate/) : Template Based Validation Framework for Vue.js
* <b>Back End</b>
    - [Python](https://www.python.org/)
        + [Django](https://www.djangoproject.com/)
* <b>DB</b>
    - [MySQL](https://www.mysql.com/)
- - -

# 11. Blog Posts
- - -

# 12. Coming Up
I plan to learn the following:
* <b>Overall</b>
    - * [Web Developer Roadmap](https://github.com/cmdlhz/developer-roadmap)       
* <b>Front-end</b>
    - CSS
        + [Flexbox](https://flexbox.io/) by Wes Bos
        + [CSS Grid](https://cssgrid.io/) by Wes Bos
    - JavaScript
        + [30 Day Vanilla Coding Challenge](https://javascript30.com/) by Wes Bos | [GitHub](https://github.com/wesbos/JavaScript30) 
    - [TypeScript](https://www.typescriptlang.org/) : a typed superset of JavaScript that compiles to plain JavaScript
        + [TypeScript Basics](http://bit.ly/2Uc9PLx) by Java Brains
        + [Make a Blockchain by using TypeScript](https://academy.nomadcoders.co/p/build-a-blockchain-with-typescript) by Nomad Coders
    - [Vue Developer Roadmap](https://github.com/flaviocopes/vue-developer-roadmap)
* <b>DB</b>
    - [MongoDB](https://www.mongodb.com/) : a cross-platform document-oriented database program (<i>No SQL!</i>)
    - [PostgreSQL](https://www.postgresql.org/) :  a powerful, open source object-relational database system
* <b>Etc</b>
    - [VIM](https://www.vim.org/) : a text editor (<i>Force you to use only the keyboard!</i>)
- - -

# 13. Contributing
If you see any typos or formatting errors in the website, please do not hesitate to open a pull request and fix it! :)
- - -

# 14. License
This project is open source and available under the [MIT License](https://github.com/cmdlhz/portfolio_website_ver2/blob/master/LICENSE).
- - -

2019 © Jen Lim 