# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > The entrypoint to a Vue application is the main.js file

02. What is the difference between a vue `component` and `page`?

  > A component is an individual thing (like a form or a CarCard from gregslist) while a page is generally a serperate page of your website

03. What is ***Component-Based Architecture***?

  > Component-Based Architecture is a design method that utilizes components that can be reused several times to speed up the front-end development process

04. What are the three tags that make up a Vue component?

  > The template (html), the script (JS), and the style (SCSS)

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > Lifecyce hooks are things like onMounted, onUnmounted, etc. They are used to add functions when loading to the page or when doing some other functionality.

06. Which component in Vue does the vue-router use to mount pages onto?

  > loadpage()

07. What is the difference between the `AppState` and the state object within a component?

  > Appstate is what is stored locally, while the state object within a component is ???

08. What is the responsibility of `Services` in our Vue projects?

  > The exact same as MVC, works with data. Can get, delete, post, and push

09. What are ***props*** and how are they used? Provide an example

  > Props are custom attributes you can register on a component. An example would be props: { car: {type: Object, required:true}}, this would allow us to utilize the properties of car such as an ID or a make / model

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > we would use the computed method to create watchable objects
