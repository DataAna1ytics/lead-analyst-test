## Lead Web Analyst Competency Test

#### Task 1. Floats.

- [ ] Please explain why this code `console.log(0.1 + 0.2 == 0.3);` outputs `false` in console? 
- [ ] Please suggest fix to make this expression working as expected.

#### Task 2. Sum function.

- [ ] Write a `sum` function which will work properly when invoked using either syntax below: 

```javascript
console.log(sum(2,3)); // Outputs 5 
``` 


#### Task 3. Loops.

Consider you have code snippet like this: 

```javascript
for (var i = 0; i < 5; i++) {
  var btn = document.createElement('button');
  btn.appendChild(document.createTextNode('Button ' + i));
  btn.addEventListener('click', function(){ console.log(i); });
  document.body.appendChild(btn);
}
```

- [ ] What will be the output when user clicks on `Button 1` and why? 
- [ ] Please, suggest a fix to get the expected behavior.

#### Task 4. Cache buster function.

Write a JS function `cachebuster`.
- [ ] The function should return new unique value (string or integer) every 5 minutes. See example below.
- [ ] Make this function as short as it is possible.


```javascript
function cachebuster() {
 // your code goes here
}

console.log(cachebuster()); // Called immediately, outputs string or integer, e.g. "abcd" or 1234
console.log(cachebuster()); // Called after 1 minutes, outputs the same string: "abcd" or 1234
console.log(cachebuster()); // Called after 2 minutes, still outputs: "abcd" or 1234

// ...

console.log(cachebuster()); // Called after 5 minutes, outputs new unique value: e.g. "abce" or 1235
console.log(cachebuster()); // Called after 6 minutes, outputs previous value: "abce" or 1235

// ...

console.log(cachebuster()); // Called after 10 minutes, outputs another one new unique value, like "abcf" or 1236

```

#### Task 5. Extracts all query strings from URL

Write a JavaScript function which extracts all query strings from URL and push them into a JavaScript object named as 'datalayer' as key values.

Example URL:

```html
http://www.datalicious.com/?pia.ca=72208039&pie.de=cbartens@datalicious.com&pin.gn=Christian&pin.fn=Bartens&pip.de=&oi.na=&ps.na=&pl.ci=&pl.re=&pl.co=&utm_source=purl&utm_medium=purl&utm_campaign=purl
```

#### Task 6. Data layer Object

Write a JavaScript function which takes 'datalayer' object from task 1 and convert them in image tag as demonstrated below and append as child to 'body' tag.

```html
<img src="https://example.com/datacollector?pia.ca=72208039&pie.de=cbartens@datalicious.com&pin.gn=Christian&pin.fn=Bartens">
```

#### Task 7. Store and retrieve the data layer

Write a JavaScript function to store and retrieve the 'datalayer' object from task-1 HTML5 storage.


#### Task 8. Unit tests

Bonus point if you write unit-tests for each of these tasks.


#### Task 9. Native JavaScript functions

Can you write down any native JavaScript functions that work in Chrome/Firefox and don't work in Internet Explorer or visa-versa?



## Instructions

- Please clone this repo in a new `Bitbucket` (or `GitHub`) private repo.
- Edit `README.md` file to provide answers on tasks `Tasks 1-9`. 
- Please use native JavaScript and not jQuery or similar libs
- Please grant access to your private repo for a GH or BitBucket user `abhishektiwari` so we can review your work. 

We suppose this test require from 3 to 4 hours. Thanks in advance for your time spent on this test! 
