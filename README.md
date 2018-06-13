# DeDuplicateArrayOfStrings
The package removes duplicate string values from the array supplied to it and returns the original array with blanks for the duplicates.

Method1: DeDuplicateArrayOfStrings

Parameter: Array

Method2: RemoveDuplicateValuesIn2ArraysAndMerge
Parameters: array1,array2

Method3: RemoveDuplicateValuesIn3ArraysAndMerge
Parameters: array1,array2,array3

v1.0.7 is es6
v1.0.8 is js

usage 
```javascript
// Method 1
const deDupe=require('deDuplicateArrayOfStrings')
var duplicatearray=[' ',' ','en','es','en','fr','es','en','en','fr','fr','Spectre','Pirates of the Caribbean','Spectre','Avatar','Avatar',
    'Sam Worthington','Denzel Washington','en','Avatar','Sam Worthington','Sigourney Weaver','Denzel Washington','Sam Worthington',
    'Sam Worthington']
    
var deduplicatedarray=deDupe.DeDuplicateArrayOfStrings(duplicatearray)

// Method 2 
var duplicatearray1=['en','es','en','fr','es','en','en','fr','fr']
    var duplicatearray2=['Spectre','Pirates of the Caribbean','Spectre','Avatar','Avatar']
    var duplicatearray3=['Sam Worthington','Denzel Washington','Sam Worthington','Sigourney Weaver','Denzel Washington','Sam Worthington']
    var result=deDupe.RemoveDuplicateValuesIn3ArraysAndMerge(duplicatearray1,duplicatearray2,duplicatearray3)

// Method 3
var duplicatearray1=['en','es','en','fr','es','en','en','fr','fr']
    var duplicatearray2=['Spectre','Pirates of the Caribbean','Spectre','Avatar','Avatar']
    var result=deDupe.RemoveDuplicateValuesIn2ArraysAndMerge(duplicatearray1,duplicatearray2)
```

##Install with [npm](http://npmjs.com)
v1.0.7 is es6
v1.0.8+ is plain js

```javascript
$ npm intall --save-dev deduplicatearrayofstrings
```
![Test Result](https://github.com/ravichandranjv/DeDuplicateArrayOfStrings/blob/master/dedupetest-pass.GIF)

![Usage](https://github.com/ravichandranjv/DeDuplicateArrayOfStrings/blob/master/usage.GIF)

##Author: **Ravichandran JV**
*License: ISC*
