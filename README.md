## Stephan Taylor's: CPNT-262-Achievement-6

### Thoughts

### Struggles with this achievement

- There are a couple of things that initially gave me some trouble. First and foremost, the linting was a major struggle.
  - No matter what I did, most of the content in my components had squiggly lines.
  - Patrick let us know that to follow this link [link](https://eslint.vuejs.org/user-guide/) - This let us know to instill `npm install --save-dev eslint eslint-plugin-vue` then add `.eslintrc.js` and add the following content within: `module.exports = { extends: [ // add more generic rulesets here, such as: // 'eslint:recommended', "plugin:vue/vue3-recommended", // 'plugin:vue/recommended' // Use this if you are using Vue.js 2.x. ], rules: { // override/add rules settings here, such as: // 'vue/no-unused-vars': 'error' }, }; `

### Attributions

- Patrick, Tony, and Maryam all helped one another with solving the first issue. With Patrick ultimatesly finding the solution that worked
