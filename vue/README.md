# Vue.js

## Top Tips

- Soon

## Essential Links

- [Vue.js](https://vuejs.org/)

- [Template Syntax](https://vuejs.org/guide/essentials/template-syntax.html)

- [VueMastery CheatSheets](vuemastery.com/vue-cheat-sheet/)

## Useful Links

- [Placehold](https://placehold.co/)

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

## Important parts inside app

- setup
- data (must return an object)
- methods (functions)
- computed (real-time calculated expressions in the form of functions)
- props (expected objects definition, should include type and required)