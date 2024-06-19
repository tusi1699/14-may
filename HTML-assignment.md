##  1.Are the HTML tags and elements the same thing?

### ans.

=> HTML tags are building blocks of HTML pages.This tags usually exist in pairs consisting of a starting and a ending tag.all HTML tags must enclosed with <>these brackets  for example:
```

![alt text](https://github.com/tusi1699/14-may/blob/main/HTML-assignment.md/src/common/images/tag.png "Logo Title Text 1")
```

=> HTML elements are components that are used in html page.And HTML elements are collection of stating tag, attributes, end tag, content between them. For ex :
```
<b>this is bold tag</b>
```


## 2. What are tags and attributes in HTML?

### ans.

     =>  Tags are define the structure and meaning of the content they enclose.

     =>Attribute are provide additional information.

#### Example:
```
 <img src="image/nature.jpeg">
```    
   in this example "src" is attribute and img is a tag.

## 3. What are void elements in HTML? with example.

### ans.

    => A void element is a self closing tag.void element only have a start tag.a void element must not have a end tag.

### Example:

    <br/>, <hr/>

## 4. What are HTML Entities? with example.

### ans.

=> HTML entities are provide a wide range of characters,allowing you to add icons, geometric shapes,mathematical operators.

### Example:
```
&copy; &reg; &trade;
&commat; &para; &sect; &#8451;
```

&copy; &reg; &trade;
&commat; &para; &sect; &#8451;

## 5.What are different types of lists in HTML? with example.

### ans.

=> There are three types of lists in HTML.

1.Unordered list(ul)

2.Order list(ol)

3.Description list(dl)

### Example of HTML Unordered list
```
<h2>List  of FruitS</h2>
<ul>
        <li>Mango</li>
        <li>Banana</li>
        <li>Apple</li>
        <li>Watermalon</li>
        <li>Orange</li>
    </ul>
```

    

<h2>List  of FruitS</h2>
<ul>
        <li>Mango</li>
        <li>Banana</li>
        <li>Apple</li>
        <li>Watermalon</li>
        <li>Orange</li>
    </ul> 
 
### Example of HTML ordered list
```
<h2>List of Fruits</h2>
   <ol type="A">
    <li>Mango</li>
    <li>Banana</li>
    <li>Apple</li>
    </ol>
```
<h2>List of Fruits</h2>
   <ol type="A">
    <li>Mango</li>
    <li>Banana</li>
    <li>Apple</li>
    </ol>

### Example of HTML Description list
```
<dl>
    <dt>Mango</dt>
    <dd>A orange color fruit. Mango is a king of fruits</dl>
```
 <dl>
    <dt><b>Mango</b></dt>
    <dd>A orange color fruit. Mango is a king of fruits</dl>

## 6. What is 'class' attribute in HTML?With Example.

### ans.
=> The  HTML class attribute specifies one or more class names for an element.it is used to point to  a class in a style sheet. The Class name used by CSS and JavaScript to do some tasks for HTMl elements.

### Example:
```
<!DOCTYPE html>
<html>

<head>
	<style>
		.country {
			background-color: black;
			color: white;
			padding: 7px;
		}
	</style>
</head>

<body>
	<h2 class="country">INDIA</h2>

	<p>
		India has taj mahal that is most popular in the world.
	</p>

	<h2 class="country">London</h2>

	<p>
		london is the capital of england.
	</p>

	<h2 class="country">UNITED STATES</h2>

	<p>
		United States has the third largest
		population in the world.
	</p>
</body>

</html>
    

```   

    

## 7.What is the difference between the 'id'  attribute and the 'class' attribute of HTML elements?With example.

### ans.
=> A class name can be used by multiple HTML elements.

=>A id name must only be used by one HTML element within the page.

###  Example:
#### HTML 'id' attribute
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1 id="frtnd">front end developer</h1>
</body>
</html>
```

  
 
#### HTML class attribute
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1 class="frtnd">front end developer</h1>
    <h2 class="webdvlpr">web developer</h2>
    
</body>
</html>
```       


## 8.What are the various formatting tags in HTML?

### ans. 
```
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text
```
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text




##  9.How is cell padding different from cell spacing? with Example.

### ans.
=> Cellpadding specifies the space between the border of a table cell and its contents.

=>cellspacing specifies the space between cells.

### Example:
```
<title>table</title>
    <caption>A test table with merged cell</caption>
</head>
<body>
    <table border="2" cellpending="5" cellspending="6">
    <thead>
        <tr>
            <th rowspan="2"></th>
            <th colspan="2">avarage</th>
            <th rowspan="2">red eyes</th>
        </tr>
        <tr>
            <th>hgight</th>
            <th>weight</th>
        </tr>
        <tr>
            <td>males</td>
            <td>1.9</td>
            <td>.003</td>
            <td>40%</td>
        </tr>
<tr>
       <td>females</td>
       <td>1.7</td>
    <td>.002</td>
    <td>43%</td>
</tr>
    </thead>
    </table>
```   
 
 <body>
    <table border="2" cellpending="5" cellspending="6">
    <thead>
        <tr>
            <th rowspan="2"></th>
            <th colspan="2">avarage</th>
            <th rowspan="2">red eyes</th>
        </tr>
        <tr>
            <th>hgight</th>
            <th>weight</th>
        </tr>
        <tr>
            <td>males</td>
            <td>1.9</td>
            <td>.003</td>
            <td>40%</td>
        </tr>
<tr>
       <td>females</td>
       <td>1.7</td>
    <td>.002</td>
    <td>43%</td>
</tr>
    </thead>
    </table>
</body>




##  10.How can we club two or more rows or columns into a single row or column in an HTML table? with Example.

### ans.

=> To merge two or more rows into a single row using the rowspan attribute .

=> To merge two or more columns into a single column use the colspan attribute.

### Example:
```
 <table border="2" align="center">
        <tr>
            <th colspan="6">time table</th>
        </tr>
        <tr>
            <th rowspan="6">hours</th>
            <th>monday</th>
            <th>tuesday</th>
            <th>wed</th>
            <th>thu</th>
            <th>fri</th>
        </tr>
        <tr>
           <td>math</td>
           <td>sci</td>
           <td>math</td>
           <td>sci</td>
           <td>arts</td>
        </tr>
        <tr>
            <td>math</td>
           <td>sci</td>
           <td>math</td>
           <td>sci</td>
           <td>arts</td>
           </tr>
        <tr>
        <td colspan="5" align="center">lunch</td>
        </tr>
        <tr>
            <td>math</td>
            <td>sci</td>
            <td>math</td>
            <td rowspan="5 " colspan="5">project</td>
        </tr>
        <tr>
            <td>math</td>
            <td>sci</td>
            <td>math</td>
        </tr>
    </table>
</body>
```
<table border="2" align="center">
        <tr>
            <th colspan="6">time table</th>
        </tr>
        <tr>
            <th rowspan="6">hours</th>
            <th>monday</th>
            <th>tuesday</th>
            <th>wed</th>
            <th>thu</th>
            <th>fri</th>
        </tr>
        <tr>
           <td>math</td>
           <td>sci</td>
           <td>math</td>
           <td>sci</td>
           <td>arts</td>
        </tr>
        <tr>
            <td>math</td>
           <td>sci</td>
           <td>math</td>
           <td>sci</td>
           <td>arts</td>
           </tr>
        <tr>
        <td colspan="5" align="center">lunch</td>
        </tr>
        <tr>
            <td>math</td>
            <td>sci</td>
            <td>math</td>
            <td rowspan="5 " colspan="5">project</td>
        </tr>
        <tr>
            <td>math</td>
            <td>sci</td>
            <td>math</td>
        </tr>
    </table>
</body>
    
        

## 11.What is the different between a block-level element and an inline element?

### ans.

=> A block element takes up the full width available, and has a line break before and after.

####  Example:
```
<br> 
<hr>
<p></p>
<div></div>
<h1></h1> to <h6></h6>
```

=> An inline element does not have line break before and after it,and only takes up as much as necessary.

#### Example:

```
<a></a>
<b></b>
<u></u>
<i></i>
<label></label>
```


## 12. How to create a Hyperlink in HTML? with Example.

### ans.

=> The anchor tag define as a hyperlink.which is used to link one page to another. which indicate the link destination.

### Example:
```
<body>
<a href="https://www.w3schools.com/">visit w3 schools</a>
</body>
```
<body>
<a href="https://www.w3schools.com/">visit w3 schools</a>
</body>


## 13. What is the use of an iframe tag? with Example.

### ans. 

=>The iframe is use to load content from another site within the page.

### Example:
```
<body>
   <br/>
   <iframe src="html_intro.html" frameborder="0"></
   <iframe src="https://www.wscubetech.com/"
   frameborder="0"
   height="500px"
   width="900px"
   <body/>
  ```
  

## 14. What is the use of a span tag? with Example.

### ans.

=> A span tag is used for structuring and styling content.The span tag is an inline container used to mark a part of text or a section within a document for applying specific styles or scripting.


### Example:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>Welcome to GFG</h2>
    <span style="background-color: blueviolet;">Geeks for geeks</span>
</body>
</html>
```


## 15. How to insert a picture into a background image of a web page? with Example.

### ans.

=> The starting```<body>``` tag in your html file.type ```<body background=" ">``` give the path of the image  we want to add.

###  Example:
```
<body
    background="pict-county-pizza-isolated-transparent-background_191095-32844.avif">
</body>
```

## 16.How are active links different from normal links?

### ans.

=> A normal link is just a line of code that contains a pointer to another resource.

=> An active link is that line of code in action,opening that other resource.

## 17. What are the different tags to separates sections of text?

### ans.

=> There are three tags used to separate the texts.

=>```<br>``` tag – It is used to separate the line of text. It breaks the current line and shifts the flow of the text to a new line.


=>```<p>``` tag–This tag is used to write a paragraph of text.

=>```<blockquote>``` tag–This tag is used to define large quoted sections.

## 18. What is SVG?

### ans.

=> SVG stands for a scalable vector graphics.

=> SVG used to define vector-based graphics for the web.

=>SVG defines graphics in XML format.

## 19.What is the different between HTML and XHTML?

### ans.

=> HTML is a markup language used to create web pages snd other information that can be displayed in a web browser.

=>XHTML is a markup language that is a stricter version of HTML and conform to XML syntax.

## 20. What are logical and physical tags in HTML?

### ans.

=> Logical tags are used to add some logical or semantic value to the text.

#### Example:
```
<b></b> 
<i></i>
<u></u>
```

=> Physical tags are used to provide the visual appereance to the text. 


#### Example:
```
<strong></strong>
<em></em>
<ins></ins>
<q></q>

```






# HTML EXAMPLE:

```
 <title>programs</title>
    <style>
        *{ 
       table{
        text-align: center;
       }     
        }
    </style>
</head>
<body>
    <table border="1">
        <thead>
            <tr>
                <th rowspan="2">Home</th>
                <th rowspan="2">about</th>
                <th rowspan="2">contact</th>
                <th rowspan="2">help</th>
                <th rowspan="2">store</th>
                <th style="background-color: red;" colspan="2">download</th>
            </tr> 
            <tr style="background-color: red;">
                <td colspan="2">app</td>
            </tr>
            <tr>
                <td colspan="6">
                <img src="margherita-pizza-with-argula-and-prosciutto-FT-RECIPE0721-04368ec288a84d2e997573aca0001d98.jpg" height="200px" width="100%">
            </td>
            </tr>
            <tr>
            <td style="background-color: palevioletred;" colspan="6">contact-us-page</td>
        </tr>
        <tr>
        <td  colspan="6" background="https://img.freepik.com/free-photo/beautiful-shot-small-lake-with-wooden-rowboat-focus-breathtaking-clouds-sky_181624-2490.jpg?t=st=1718186021~exp=1718189621~hmac=daf4c4503cbc25af5c076110b2bff198bdbc6dd7e066a9819dc34053804453c7&w=740" style="height: 450px; width: 100% ;">  
            <span style="font-size: 30px; color: white; font-weight: 300;" >contact us</span>
        </td>  
    </tr>
    <tr>
        <td colspan="3">
            <label>first-name</label>
            <input type="name" id="" placeholder="Enter your name">

        </td>
        <td colspan="3">
            <label>last name</label>
            <input type="name" id="" placeholder="enter your last name">
        </td>
    </tr>
    <tr>
        <td colspan="3">
            <label>Email id</label>
            <input type="name" id="" placeholder="Enter your email">
        </td>
        <td colspan="3">
            <label>phone no.</label>
            <input type="number" id="" placeholder="enter your phone no.">
        </td>
    </tr>
    <tr>
        <td colspan="3">
            
           <label for="city">city</label> 
            <input type="text" list="city" placeholder="select your city">
            <datalist id="city">
                <option value="Rajkot">Rajkot</option>
                <option value="surat">surat</option>
                <option value="Ahmadabad">Ahmadabad</option>
                <option value="Baroda">Baroda</option>
                <option value="Bharuch">Bharuch</option>
           
            </datalist> 
        </td>
            <td colspan="3">
                <label for="gender">gender</label>
                <label for="male" >male</label>
                <input type="radio" id="male" name="gender" >
                <label for="female" >female</label>
                <input type="radio" id="female " name="gender">
                
            </td>
        </tr>
        <tr>
            <td colspan="3">
                <iframe src="https://www.yet5.com/institute-map.htm?mapid=11439" height="100%" width="100%"></iframe>
            </td>
            <td colspan="3">
   
   
   <iframe src="https://www.wscubetech.com/"></iframe>
            </td>
        </tr>
    </thead>
</table>
</body>
</html>
```
 