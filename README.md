# Animated, Responsive Prerendered Blog

Vue.js blog utilizing prerender-spa-plugin to make the blog more SEO friendly. Content updated via JSON feed, which can be supplied via a headless CMS.

[Demo](https://jsnspr-vue-prerender-blog.netlify.com/)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## Customizing Disqus

To use your own Disqus account for comments, create an account on [Disqus](https://disqus.com/), click on the user icon in the top right hand corner and select "Install on Site", give it a name and copy, open src/components/BlogPost.vue, and replace the string following shortname with what you copied and the first part following :url= with the address of where your site is hosted. 
