## Stephan Taylor's: CPNT-262-Achievement-6

### Thoughts on Vue

Now that I have used vue for half the week now, I can honestly say I love it! The ease of use of it is just outstanding. It makes building a website seemingly easy with little to know hiccups besides learning how to use components effectively.

- For future vue projects, I will plan out what I want my site to look like and develop components accordingly.
- In addition, I do not fully understand how to use `slots` and `v-for`. Upon further use, I will watch some tutorials on on how to use these properly.

### Struggles with this achievement

- There are a couple of things that initially gave me some trouble. First and foremost, the linting was a major struggle.
  - No matter what I did, most of the content in my components had squiggly lines.
  - Patrick let us know that to do the following:
    1. Go to this [link](https://eslint.vuejs.org/user-guide/)
    2. Then install using `npm install --save-dev eslint eslint-plugin-vue` then add `.eslintrc.js` and add the following content within:
    3. Then copy this into the `eslintrc.js` file ![screencap](https://github.com/Stayl045/cpnt-262-achievement-6/blob/219a0a4d33ff400696448d2a488eaeca8d987ba6/esling-config.png)
  - Doing all of this resolved the issue!
- Another issue was getting tailwind to work via the plugin installation. Doing it this way seemed to have not worked for me.
  - To resolve this i used `vue add tailwind` then following the steps. This resolved the issue

### Attributions

- Patrick, Tony, and Maryam all helped one another with solving the first issue. With Patrick ultimately finding the solution that worked
