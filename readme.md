# wordcamp-rotterdam-2019-css

## Parsing Less

We are parsing the LESS to `dist/styles/style.css` so load that file via Remote CSS.

### Via Gulp

- In `development` `npm install`
- Then `node_modules/.bin/gulp` or `node_modules/.bin/gulp watch`

### Via an App
Or just use your favourite LESS parser App like http://koala-app.com or https://codekitapp.com/ (trail = 30 days)


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
