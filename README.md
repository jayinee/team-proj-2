
# Encyclopedia  `<h1>`

##Usage:


The header "h1" tag in HTML is a first and largest tag of the post.
It will be having main title as it is a largest text of the document.
In HTML coding the header tags from h1 to h6 form a hierarchy.
If anybody will break the tag numbers the heading structure will become unorganized.

A heading element implies all the font changes, paragraph breaks and any white space necessary to render the heading. The heading elements are H1, H2, H3, H4, H5 and H6 where H1 is the highest and important first level tag and H6 is the least important tag. 

##Attributes:



##Attribute Values:


|  Sr. No.|   Value    |Description                             |
|---------|------------|----------------------------------------|
|   1	  | Left       | Left aligns the heading                |
|   2	  | Right      | Right aligns the heading               |
|   3	  | Center     | Center aligns the heading              |
|   4	  | Justify    | The heading is justified to both margin|


```<h1 align=”left|right|center|justify”>```

##Example:

```
<h1> Modern Developer </h1>

```

*Default CSS settings of h1 tag:*

```
h1 {
display: block;
font-size: 2em;
margin-top: 0.67 em;
margin-bottom: 0.67 em;
margin-left: 0;
margin-right: 0;
font-weight: bold;
}

```
# Encyclopedia  `Border-bottom-color`

##Usage:

It is one of the properties of CSS. It sets the color of an element’s bottom border. Its default value is color of the element. 

##Prerequisite:
Always declare the border-style property before border-bottom-color property. 

##Properties and Values:
	
	
|Sr. No.|Value	        |Description                                                            |
|-------|---------------|-----------------------------------------------------------------------|
|1	|Color	        |Specifies background color. Default color is the color of the element. |
|2	|Transparent    |Specifies that the border color should be transparent.                 |
|3	|Initial	|Sets this property to its default value.                               |
|4	|Inherit	|Inherits this property from its parent element.                        |

##Syntax:

```
Object,style.borderBottomColor = “color|transparent|initial|inherit”
```

*The below list is showing list of all browsers which supports this property.*

|Property	        |Chrome	|IE/Edge |FireFox |Safari	|Opera|
|-----------------------|-------|--------|--------|-------------|-----|
|Border-bottom-color	|1.0	|4.0	 |1.0	  |1.0	        |3.5  |

##Examples:

A.Change the color of the bottom border of a <div> element to blue:

```
Document.getElementById (“div1”).style.borderBottomColor = “blue”;
```
B.In this example assigning black color to bottom border of paragraph.

```
#tutorial p{
Border-bottom-color=#000;
}

```

# Encyclopedia  `Infinity`

##Description:

Infinity is a property of the global object, i.e. it is a variable in global scope.

The initial value of Infinity is Number.POSITIVE_INFINITY. The value Infinity (positive infinity) is greater than any other number. This value behaves mathematically like infinity; for example, any positive number multiplied by Infinity is Infinity, and anything divided by Infinity is 0.

Per the ECMAScript 5 specification, Infinity is read only (implemented in JavaScript 1.8.5 / Firefox 4).

The global Infinity property is a numeric value representing infinity.

|Property attributes of Infinity|   |
|-------------------------------|---|
|Writable	                |no |
|Enumerable	                |no |
|Configurable	                |no |

##Examples:

```
console.log(Infinity         ); /* Infinity */  
console.log(Infinity + 1     ); /* Infinity */  
console.log(Math.pow(10,1000)); /* Infinity */  
console.log(Math.log(0)      ); /* -Infinity */  
console.log(1 / Infinity     ); /* 0 */

```

##Syntax:

```
Infinity 
```
##Specifications:


|Specification	                                       |Status	             |Comment                                           |
|------------------------------------------------------|---------------------|--------------------------------------------------|
|**ECMAScript 1st Edition (ECMA-262)**	               |Standard	     |Initial definition. Implemented in JavaScript 1.3 |
|**ECMAScript 5.1 (ECMA-262)**                         |Standard             |                                                  |    
|**ECMAScript 2015 (6th Edition, ECMA-262)**           |Standard             |                                                  |     
|**ECMAScript 2017 Draft (ECMA-262)                    |Draft                |                                                  |


##Browser compatibility:


|Feature	   |Chrome	|Firefox(Gecko)	|Internet Explorer	|Opera	|Safari|
|------------------|------------|---------------|-----------------------|-------|------|
|Basic support	   |(Yes)	|(Yes)	        |(Yes)	                |(Yes)	|(Yes) |
