# Vue.js

## Top Tips

- Soon

## Essential Links

- [Vue.js](https://vuejs.org/)

- [Template Syntax](https://vuejs.org/guide/essentials/template-syntax.html)

- [VueMastery CheatSheets](vuemastery.com/vue-cheat-sheet/)

- [VueMastery Crashcourse](https://www.youtube.com/watch?v=bzlFvd0b65c)

## Useful Links

- [Placehold](https://placehold.co/)

## Installing Vue

```
npm install -g @vue/cli
```

Find your vue cli tool in your user profile path
```
C:\Users\username\AppData\Roaming\npm
```
or
```
%appdata%\npm
```

## Starting a Vue project

Make sure you have the vue cli installed and you can call the cli to start a project using the following:

```
vue create name-of-app
```

At the labs, you will have to reference the entire user path to get to your appdata folder to access vue.cmd after installing the cli:

```
C:\Users\username\AppData\Roaming\npm\vue.cmd create name-of-app
```

## Expressions

{{ expression }}

## Data Binding

```vue
v-bind:src="imageSrc"
:src="imageSrc"
```

## Conditionals

```vue
v-if="available"
v-else
v-show="available"
```

## Loops

```vue
v-for="item in list"
v-for="detail of item"
```

(you can use in and of for loops)

- use :key binding with an id, or with optional (item, index) option

## Listeners / Actions

```vue
@mouseover="action"
```

## Emitting events and data payloads

```vue
this.$emit("new-event", payload)
```

### Two-way binding

```vue
v-model="expression"
```

## Important parts inside app

- setup
- data (must return an object)
- methods (functions)
- computed (real-time calculated expressions in the form of functions)
- props (expected objects definition, should include type and required)