CSS for the Soul
----------------

Install dependencies 
```
npm install
```

Then run the app
```
npm start
```
and open up `http://localhost:3000`

The content for this microsite has been written in [jade](http://jade-lang.com) and [less](http://lesscss.org). Layout and partials can be found under `views`. 

To compile components, run
```
npm run-script components
```
This generates public/javascripts/components.js

To generate the site, run 
```
npm run-script pages
```

This generates `public/index.html`. Thus the `public` folder can be directly served.  