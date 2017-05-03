# Countrs
A library of counting related tools written in vanilla JavaScript

This is a very simple counter tool with count up, count down, and clock functionality


# Usage:
It is very easy to use Countr.

First, download the files and add them to your page
```
<script src="/path/to/countr.js"></script>
```

Next, you need to create an element for the counter (note: this exmple is for the counter up function)
```
<div class="container">
    <h2><span class="counter-up">40</span></h2>
    <p>Of this thingy</p>
</div>
```

Finally, initialize the counter:`counterUp(el, speed, delay);`

In the HTML:
```
counterUp('counter-up', 2500, 1000);
```
Or in a seperate file:
```
(function(){
  counterUp('counter-up', 2500, 1000);
})();
