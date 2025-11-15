# DKMoji
**DKMoji** is a set of emojis developed by DKon.app. These emojis are designed in a unique style and are used in the DKon.app applications and website, as well as on other platforms. The main advantage of DKMoji is that they are provided as open-source, allowing developers and users to freely use them in their projects.

You can easily start using our emojis!

## Start 

To start using them, you need to include the JavaScript script in your website or project.

```html
<script src="https://res.dkon.app/dkon-emodji/dkmoji.js"></script>

```



You should also add this script at the bottom of the page.
`emoji-container` is the class that contains the text with emojis.

```html
<script>
    document.addEventListener("DOMContentLoaded", function() {
        const posts = document.querySelectorAll('.emoji-container');
        posts.forEach(post => {
            dkmoji.parse(post);
        });
    });
</script>
```

By default, all images are sized 72x72!  
To adjust the height and width of the emojis, use the following CSS:

```html
<style>
    .DKmoji {
        width: 17px;  
        height: 11px; 
    }
</style>

```

You do not need to download our JS; everything is loaded from our CDN servers!

You can use the emojis in any project!

## Screenshot 

<img src="https://filecloud-62-ars-cont-st.dkon.app/wp-cont/cloud62/dkon.app_074dd2527e6be4b6_DKon.app_dc5e7b43fc.png" />

## Support 

Here you will find even more useful resources for your projects: [https://dkon.app/dev](https://dkon.app/dev)  
