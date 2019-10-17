# JavaScript
- used to code user interaction
- action
- sets up rules in "if this, then this" format, provides outcomes for defined inputs

a JS rule would look like
```
var today = new Date ();
var hourNow= today.getHours();
var greeting;

if (hourNow > 18) {
    greeting= 'Good evening!';
}
else if (hourNow >12) {
    greeting= 'Good afternoon!';
}
else if (hourNow > 0) {
    greeting= 'Good morning!'
}
else {
    greeting= 'Welcome!'
}

document.write('<h3>' + greeting + '</h3>');
```
and should appear in your html as 
```
<!DOCTYPE html>
<html>
    <head>
        <title>Constructive & amp; Co.</title>
        <link rel="stylesheet" href="css/c01.css" />
    </head>
    <body>
        <h1>Constructive & amp; Co.</h1>
        <script>document.write('<h2>Welcome!</h3>');
        </script>
        <p>For all orders and inquiries please call
            <em>555-3344</em></p>
    </body>
</html>
```
the HTML `<script>` element is used to load the JavaScript file into the page.  It has an attribute called `src` whose value is the path to the script you created

### data types
- string: piece of data inside single quotes... ex) 'welcome'
- boolean: true or false, machine code that translate to a yes/no response
- numbers

### useful commands
- `typeof *variable*` will tell you what type of data (string, number, boolean)
- `===` strict equals
