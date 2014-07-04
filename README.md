<h1>Multi-Column-Select</h1>

<h4>Jquery CSS Multi Column Select Box</h4>
<p>A Simple plugin that will hide the Select control and then display a multicolumn dropdown (css)</p>
<p>Uses the original form control so will work if JS is not enabled and the form can be process as normal</p>


<h2>Installation</h2>

<pre>

Load the CSS:
"MultiColumnSelect/MultiColumnSelect.css"

Include js plugin:
"MultiColumnSelect/MultiColumnSelect.js"

</pre>

<h2>Set up your HTML</h2>

```
    <form action="test.php" method="GET">

    <div class="selectcontrol">
        <select name="car">
                <option value="Audi">Audi</option>
                <option value="Bugatti">Bugatti</option>
                <option value="Chrysler">Chrysler</option>
                <option value="Daihatsu">Daihatsu</option>
                <option value="Ford">Ford</option>
                <option value="GM">General Motors</option>
                <option value="Honda">Honda</option>
                <option value="Infiniti">Infiniti</option>
                <option value="Jeep">Jeep</option>
                <option value="Kia">Kia</option>
     </select>
    </div>
    
        <input type="submit" value="Submit" />
    
    </form>

```
Wrap the select control with a div and give that container an ID or class

<h2>Call the plugin</h2>

```javascript
$(".selectcontrol").MultiColumnSelect({

            menuclass : 'multicolumnselect',     // class given to control
            openmenu : 'openmenubutton',         // used to toggle menu open/closed
            openmenutext : 'Choose An Option',   // Text for toggle menu button
            menucontainer : 'menucontainer',     // Container Class
            menuitem : 'menuitem',               // Item Class
            hideclass : 'hidden',                // hide Class
            openclass : 'open',                  // Open Class
            clearclass : 'clear',                // Clear Class
            duration : 200                       // Animation Duration

});
```


<h2>Tested on</h2>
<ul>
<li>IE7+</li>
<li>Safari</li>
<li>Firefox </li>
<li>Chrome</li>
</ul>


<h2>License</h2>

<p>The MIT License (MIT)</p>
