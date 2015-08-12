# systemjs-domReady
domReady plugin for Systemjs

Returns a promise that is fulfilled when the DOM is loaded.

## Usage
````
System.import('domReady.js')
.then(function(){
  document.querySelector('body > form').addEventListener('submit', function(ev){ ev.preventDefault(); });
});
````
