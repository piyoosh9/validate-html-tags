# Validate HTML Tags
Utility functions to escape custom tags in a string or check if any string contains valid or custom tags.


## Installation
```shell
$ npm i validate-html-tags
```

## How to use

#### 1. Method to replace custom tags with &lt; and &gt; and return the changed string 
```js
validateHTMLTags.escapeCustomTags('Send a <custom> and a valid <html> tag here to test!')
```

#### 2. Method to check if string contains any valid html tag or not 
```js
validateHTMLTags.isValidTag('Send a <custom> and a valid <html> tag here to test!')
``` 

#### 3. Method to check if string contains any custom html tag or not 
```js
validateHTMLTags.isCustomTag('Send a <custom> and a valid <html> tag here to test!')
```

## Misc

#### Considered Valid HTML tags list
We are considering W3Schools valid HTML elements, ref [here](https://www.w3schools.com/tags/ref_html_dtd.asp).
