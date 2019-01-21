
# Editing the CSS 
We are parsing the SCSS files to [`dist/styles/style.css`](dist/styles/style.css) so load that file via Remote CSS functionality of the WordCamp site.
1. So if you want to alter something to the styling, edit that file.
2. The CSS gets updated automatically via GitHub WebHooks. 
If it doesn't gets updated, then re-save the Remote CSS via https://2019.rotterdam.wordcamp.org/wp-admin/themes.php?page=remote-css


> I, Jaime, used the SCSS / Gulp while developing the initial styling because that sped-up the progres for me.


## HTML elements
These are custom build HTML blocks that you have to enter into the WYSIWYG editor.

### Tickets row
 

```
<div class="row-full-width row-tickets">
    <div class="container-inner">
        <h2><a href="/tickets">Haal hier je ticket!</a></h2>
        <hr />
        <h2><a href="/tickets">Get your ticket here!</a></h2>
        <a href="/tickets"><img class="tickets aligncenter wp-image-347 size-medium" src="tickets-liggend-small-300x225.png" alt="" width="300" height="225" alt="Haal hier je ticket." /></a>
    </div>
</div>
```

# Gulp

- In `development` `npm install`
- Then `node_modules/.bin/gulp` or `node_modules/.bin/gulp watch`

## Via an App
Or just use your favourite LESS parser App like http://koala-app.com or https://codekitapp.com/ (trail = 30 days)
