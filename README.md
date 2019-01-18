# A Storyblok WYSIWYG Example Field-Type Plugin

This example fieldtype gives you the starting point to define 
and build your custom wysiwyg editor. I've used TinyMCE as an example 
here, which you can replace with any other wysiwyg editor.

## How to use this project in Storyblok

1. Create a new Field Type

Custom Field Type names in Storyblok are unqiue, so I've used the name `ex-wysiwyg` in this example. For you to run your own plugin you can replace the `ex-` prefix with your own prefix.

2. Replace the the example name with yours
  
Exchange: `'ex-wysiwyg'` in the Plugin.vue with your plugin name. It has to be an exact match.

3. Make sure you're on `http:app.storyblok.com` and not `https://app.storyblok.com` as your local development setup is running without ssl.

4. [Follow Step 4](https://www.storyblok.com/docs/Guides/Creating-a-field-type-plugin#local-development) on our website

## Which options are availble in the example?

[How to pass options](https://www.storyblok.com/docs/Guides/Creating-a-field-type-plugin#how-to-pass-options)

1. `debug` true/false
2. `oauthToken` Your OAuthToken if you need an file upload to Storyblok


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
https://www.storyblok.com/docs/Guides/Creating-a-field-type-plugin#how-to-develop-plugins-locally