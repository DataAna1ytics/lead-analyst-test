## Web Analyst Competency Test

## Instructions

- Please use native JavaScript and not jQuery or similar libs
- Please send us the test results in a text file
- Bonus points if you use Github or Bitbucket to version control you test results

We suppose this test require from 2 to 3 hours. Thanks in advance for your time spent on this test! 


#### Task 1. Extracts all query strings from URL

Write a JavaScript function which extracts all query strings from URL and push them into a JavaScript object named as 'datalayer' as key values.

Example URL:

```html
http://www.datalicious.com/?pia.ca=72208039&pie.de=cbartens@datalicious.com&pin.gn=Christian&pin.fn=Bartens&pip.de=&oi.na=&ps.na=&pl.ci=&pl.re=&pl.co=&utm_source=purl&utm_medium=purl&utm_campaign=purl
```

#### Task 2. Data layer Object

Write a JavaScript function which takes 'datalayer' object from task 1 and convert them in image tag as demonstrated below and append as child to 'body' tag.

```html
<img src="https://example.com/datacollector?pia.ca=72208039&pie.de=cbartens@datalicious.com&pin.gn=Christian&pin.fn=Bartens">
```

#### Task 3. Store and retrieve the data layer

Write a JavaScript function to store and retrieve the 'datalayer' object from task-1 HTML5 storage.


#### Task 4. Native JavaScript functions

Can you write down any native JavaScript functions that work in Chrome/Firefox and don't work in Internet Explorer or visa-versa?




