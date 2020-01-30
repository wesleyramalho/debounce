# debounce
A personal implementation of debounce in JavaScript

## Usage example
In this example the alert happens only after 2000 milliseconds after the user iteration stops.

```javascript
 const handleSearch = debounce(typing => {
    alert(typing);
  }, 2000);
```

Reference:
[Throttle and Debounce patterns in JS](http://loopinfinito.com.br/2013/09/24/throttle-e-debounce-patterns-em-javascript/)

