<a name="installation" class="anchor" href="#installation"><span class="mini-icon mini-icon-link"></span></a>Installation</h2>

<p>Include script <em>after</em> the jQuery library:</p>

<pre><code>&lt;script src="easyNotify.js"&gt;&lt;/script&gt;
</code></pre>


<h2>
<a name="usage" class="anchor" href="#usage"><span class="mini-icon mini-icon-link"></span></a>Usage</h2>

<p>Basic setup:</p>

```html
<div id="easyNotify"></div>  <!-- HTML -->
```

```javascript
$("#easyNotify").easyNotify(); // JS
```
<p>Options can be pass by object like:</p>

```javascript
var options = {
      title: "Notificação",
      options: {
        body: "O melhor do Brasil são os Brasileiros.",
        icon: "icon.png",
        lang: 'pt-BR',
      }
    };

$("#easyNotify").easyNotify(options);
```

<p>Functions can be pass by param to run on methods like onclose</p>

```javascript
var myCloseInfo = function(){
    alert('this is a callback function that runs after close the notification.');
};

var options = {
      title: "Notificação",
      options: {
        body: "O melhor do Brasil são os Brasileiros.",
        icon: "icon.png",
        lang: 'pt-BR',
        onClose: myCloseInfo
      }
    };

$("#easyNotify").easyNotify(options);
```
<h2>
<a name="demo" class="anchor" href="#demo"><span class="mini-icon mini-icon-link"></span></a>Demo</h2>
<p><strong><a href="https://jsfiddle.net/gabrielr47/03rxc6n9/26/">easyNotify</a></strong> </p>
<h2>
<a name="authors" class="anchor" href="#authors"><span class="mini-icon mini-icon-link"></span></a>Author</h2>

<p><a href="http://pt.stackoverflow.com/users/17658/gabriel-rodrigues" target="_blank">Gabriel Rodrigues</a></p>

