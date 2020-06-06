# Validate HTML Tags
Utility functions to escape custom tags in a string or check if any string contains valid or custom tags.


## Installation
```shell
$ npm i validate-html-tags
```

## How to use

#### 1. Method to escape custom tags
The method will return  the changed string in which all the custom HTML tags will be replaced with lt and gt 
```js
validateHTMLTags.escapeCustomTags('Send a <custom> and a valid <html> tag here to test!')
```

#### 2. Method to check if string contains any valid html tag or not 
This method will return a boolean stating whether the given string contains any valid html tag or not
```js
validateHTMLTags.isValidTag('Send a <custom> and a valid <html> tag here to test!')
``` 

#### 3. Method to check if string contains any custom html tag or not 
This method will return a boolean stating whether the given string contains any custom html tag or not
```js
validateHTMLTags.isCustomTag('Send a <custom> and a valid <html> tag here to test!')
```

## Misc

#### Considered Valid HTML tags list
We are considering W3Schools valid HTML elements, ref [here](https://www.w3schools.com/tags/ref_html_dtd.asp).


#### Suggestions
If you have any suggestions on what more can be added to this library, write to me at - piyush@whisperingbox.com
