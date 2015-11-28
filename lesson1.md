## Lesson 1 ##

### What is JavaScript? ###
JavaScript as a language for telling computers what to do. JavaScript started when people first started making websites.
They wanted to do more than just have links between pages.

See [Example 1](http://plnkr.co/edit/pIIAPCcqBTznF1Bu8rAs?p=info)

In our first example, we have a web page with a button. When that button is pressed (on click), it will run the `sayHello()` function.
That function finds the element with the id (identifier) of "content" and changes the inside of that element to the text "Hello world". 
Don't worry about knowing what every word means. Just focus on learning one thing at a time.

```HTML
<h1>Lesson 1: <small>Example 1</small></h1>
<!-- This button element runs the sayHello() function -->
<button type="button" onclick="sayHello()">Say Hello</button>

<!-- This is the element that will contain the new text -->
<p id="content"></p>


<script>
  // This is the JavaScript code
  // The button will run this code
  function sayHello() {
    document.getElementById('content').innerHTML = 'Hello world';
  }
</script>
```

Without me explaining anymore, try to change the code (don't worry, you can always go back to the original). Let's see if 
you can change the text "Hello world" to something else.
