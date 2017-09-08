# Vue.js Study Project

Brainstorm all about vue learning processess here. Main goal is to produce an enterprise scaffold. 



## No build, just tasks, files and hopely, conversations and enough commits for us to move on

First time:
```
cd /work/folder

git clone http://github.com/marcosantana77/vuejs-brainstorm

```

In order to run the examples, you better use some sort of web server, choose as you must, recommendation goes for 

```
$ npm install -g http-server

$ cd /work/folder/example

$ http-server 

```


Folder structure:
```
.
├── README.md
└── ref
    ├── pluralsight
    │   └── 01_data_binding
    └── todomvc
        ├── angularjs
        ├── jquery
        ├── vanilla-es6
        ├── vanillajs
        └── vue
```


## Overall folder explanation 

- ref -- all reference stuff
- ref/todomvc -- todomvc implementations import: basically whatever the proposed group area of expertise, and our main goal, vuejs. Brought from  [TasteJS/TodoMVC](https://github.com/tastejs/todomvc/tree/master/examples/) - CRUD easy syntax implementation for 
- ref/pluralsight -- pluralsight laracasts code-along products and considerations


## To Do

- code-along Pluralsight VueJs Laracasts
  - 01. Data Bindings (done)
    - v-model
    - new Vue({})
    - first load, non-minified 71k :))))

  - 2. Devtools (done)
    - install [vue.js devtools chrome extension](https://github.com/vuejs/vue-devtools)
    - after extension activation, a vue icon will appear at the upper right corner
    - within devtools, a new action tab shows up: vue
    - on vuejs action tab one can have access to the whole two-way binding tree, changes are automatically reflected throughout the DOM
  - 3. Lists (on)
  - 4. Event Listeners
  - 5. Attributr and class binding
  - 6. The Need for Computed Properties
  - 7. Components 101
  - 8. Nesting components
  - 9. Exercise: Modal
  - 10. Exercise: Tabs
  - 11. Component Communication Example #1: Custom Events
  - 12. Component Communication Example #2: Event Dispatcher
  - 13. Named Slots in a Nutshell
  - 14. Single-Use Components and Inline Templates
  - 15. Webpack and vue-cli
  - 16. Hot Module Replacement
  - 17. Vue Ajax Requests With Axios
  - 18. Object-Oriented Forms: Part 1
  - 19. Object-Oriented Forms: Part 2
  - 20. Object-Oriented Forms: Part 3
  - 21. Shared State 101
  - 22. Custom Input Components
  - 23. SPA: Routing
  - 24. SPA: Backend


## Reference Links

Here is some very intersting reading on a few pattern aspects, good to keep in mind when developing big systems with Vue.JS:<br/>

### Code Splitting Pattern

[https://vuejsdevelopers.com/2017/07/08/vue-js-3-ways-code-splitting-webpack/](https://vuejsdevelopers.com/2017/07/08/vue-js-3-ways-code-splitting-webpack/)

### VueX

[https://vuex.vuejs.org/en/intro.html](https://vuex.vuejs.org/en/intro.html)
