## Lead Web Analyst Competency Test

## Instructions

- Please use native JavaScript and not jQuery or similar libs
- Please send us the test results in a text file
- Bonus points if you use Github or Bitbucket to version control you test results

We suppose this test require from 3 to 4 hours. Thanks in advance for your time spent on this test! 

#### Task 1. Floats.

- [ ] Please explain why this code `console.log(0.1 + 0.2 == 0.3);` outputs `false` in console? 
- [ ] Please suggest fix to make this expression working as expected.

#### Task 2. Sum function.

- [ ] Write a `sum` function which will work properly when invoked using syntax below: 

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


#### Task 4. Extracts all query strings from URL

Write a JavaScript function which extracts all query strings from URL and push them into a JavaScript object named as 'datalayer' as key values.

Example URL:

```html
http://www.datalicious.com/?pia.ca=72208039&pie.de=cbartens@datalicious.com&pin.gn=Christian&pin.fn=Bartens&pip.de=&oi.na=&ps.na=&pl.ci=&pl.re=&pl.co=&utm_source=purl&utm_medium=purl&utm_campaign=purl
```

#### Task 5. Data layer Object

Write a JavaScript function which takes 'datalayer' object from task 1 and convert them in image tag as demonstrated below and append as child to 'body' tag.

```html
<img src="https://example.com/datacollector?pia.ca=72208039&pie.de=cbartens@datalicious.com&pin.gn=Christian&pin.fn=Bartens">
```

#### Task 6. Store and retrieve the data layer

Write a JavaScript function to store and retrieve the 'datalayer' object from task-1 HTML5 storage.


#### Task 7. Native JavaScript functions

Can you write down any native JavaScript functions that work in Chrome/Firefox and don't work in Internet Explorer or visa-versa?




