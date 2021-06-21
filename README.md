# vue-mastery
## Intro to Vue 2
  01. The Vue Instance
    
      How to begin writing a Vue application with a Vue instance, and how to load basic data onto the webpage.
      The Vue instance is the root of every Vue application
      The Vue instance plugs into an element in the DOM
      The Vue instance’s data can be displayed using the mustache-like syntax {{ }} called an expression.
      Vue is reactive

  02. Attribute-binding
      Data can be bound to HTML attributes.
      Syntax is v-bind: or : for short.
      The attribute name that comes after the : specifies the attribute we’re binding data to.
      Inside the attribute’s quotes, we reference the data we’re binding to.

      03. Conditional Rendering
      There are Vue directives to conditionally render elements:
            v-if
            v-else-if
            v-else
            v-show
      If whatever is inside the directive’s quotes is truthy, the element will display.
      You can use expressions inside the directive’s quotes.
      V-show only toggles visibility, it does not insert or remove the element from the DOM.