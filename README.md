# Vue.js Boilerplate

I did some research in order to find the perfect folder structure, component architecture, and naming convention, I went through the Vue.js documentation, a few articles and many GitHub open source projects.

Vue.js directory structure with following packages/functionality. 

- **vuex** with modules 
- **router** with meta
- services with token based access
- environment variable
- filters.
- **pages and component** structure

This structure might be helpful in your large project/application, However Vue doesn't really restrict how you structure your code.

### Structure
```
└── src
    ├── App.vue
    ├── assets
    │   └── logo.png
    ├── components
    │   └── HelloWorld.vue
    ├── main.js
    ├── router.js
    ├── services
    │   ├── api.service.js
    │   ├── storage.service.js
    │   └── user.service.js
    ├── store
    │   ├── auth.module.js
    │   └── index.js
    └── views
        ├── About.vue
        ├── Home.vue
        └── LoginView.vue
```
### Sources
* [Structuring a Vue project — Authentication](https://medium.com/@zitko/structuring-a-vue-project-authentication-87032e5bfe16)
