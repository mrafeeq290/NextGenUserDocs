# User Guides for Markdown Lanuguage

This is a sample paragraph in Markdown 

## Lists in Markdown
 ### Family Members

  * Mohammad Rafeeq
  * Shaikh Sana
    - Zoya Ansari
    - Fawad Ansari
  * Mohammad ASif
    - Shaikh Saba
  * Mohammad Arif
    - Mohammad Ayan
    - Zara Hayat  

### Houses

1. Mohammad Arif
   - Shanit Nagar
   - Wadala
   - Khandeshwar
   - Mankhurd
   - Chembur

2. Nadeem Ansari
   - Bandra (W)
   - Oshwira
   - Wadala (Shanti Nagar)  


---

## Where does it come from?
Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard **McClintock**, a Latin professor at Hampden-Sydney College in _Virginia_, looked up one of the more obscure Latin words, consectetur, from a ~~Lorem Ipsum~~ passage, and going through the cites of the word in classical literature, discovered the *_undoubtable_* source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. `The first line of Lorem Ipsum`, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.


---

---


[Foretellix](https://www.foretellix.com)<br/>

## Basic Network Architecture Diagram with Router


![Rest API](./Images/Rest-Api-Architecture.jpg)<br> 



#### Section 1.10.32 of "de Finibus Bonorum et Malorum", written by Cicero in 45 BC

"Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia **consequuntur** magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea<br> 

_Note_: voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"


|  Name | Age  |  Emp Code |  Designation | Salary  |
|---|---|---|---|---|
| Mohammad  |30  | 105672  |  Senior Tech Writer | 60000  |
|  Gaurav | 32  | 10546  |  Survey Programmer | 70000  |
| Ram| 45|10543|Admin Assistant|85000|
| Wilson|52|10523| Human Resources Mgr| 85000|


`<h1>Hello Markdown</h1>`


---

## Hello

MY name is Rafeeqa


## Javascript Codes and Scripts in Html Pages.


```Javascript codes
<script type="text/javascript">
    var rows = prompt("How many rows for your multiplication table?");
    var cols = prompt("How many columns for your multiplication table?");
    if(rows == "" || rows == null)
   		 rows = 10;
    if(cols== "" || cols== null)
   		 cols = 10;
    createTable(rows, cols);
    function createTable(rows, cols)
    {
      var j=1;
      var output = "<table border='1' width='500' cellspacing='0'cellpadding='5'>";
      for(i=1;i<=rows;i++)
      {
    	output = output + "<tr>";
        while(j<=cols)
        {
  		  output = output + "<td>" + i*j + "</td>";
   		  j = j+1;
   		}
   		 output = output + "</tr>";
   		 j = 1;
    }
    output = output + "</table>";
    document.write(output);
    }
  </script>

```


## Javascript codes for Regular Functions

```Javascript
    var rows = prompt("How many rows for your multiplication table?");
    var cols = prompt("How many columns for your multiplication table?");
    if(rows == "" || rows == null)
   		 rows = 10;
    if(cols== "" || cols== null)
   		 cols = 10;
    createTable(rows, cols);
    function createTable(rows, cols)
    {
      var j=1;
      var output = "<table border='1' width='500' cellspacing='0'cellpadding='5'>";
      for(i=1;i<=rows;i++)
      {
    	output = output + "<tr>";
        while(j<=cols)
        {
  		  output = output + "<td>" + i*j + "</td>";
   		  j = j+1;
   		}
   		 output = output + "</tr>";
   		 j = 1;
    }
    output = output + "</table>";
    document.write(output);
    }
  
```

---

## AEM Development Content Management System


[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

## Tech

- [AngularJS] - HTML enhanced for Web Pages.
- [Ace Editor] - Awesome Web based text editor.
- [markdown-it] - Markdown Parser done right . FAst and easy to understand.
- [Breakdance](https://breakdance.github.io./brealdamce) - Html to Markdown converter . 
- [Express] - fast node.js network app framework [@tjholowaychuk] 
- [jquery] - duh


and of course Dillinger itself is open source witrh [Public repository ][dill] on GitHub


## External Links in Html

[Foretellix](https://www.foretellix.com)


---

## Images in Markdwon!

![Alt Text](./Images/Rest-Api-Architecture.jpg)

## Tables in Markdown!

|   Name  |Age     |Qualifidcation     |
|---- |-----|-----|
|     |     |     |                     |
|     |       |   |     |


## Formatting options in Markdown in !

*_this_* is **sample** paragrpah in _Markdsown_!



## codes in Markdown!

`func (
  a,b
)
`

```Javascript

Var a;
var b;

function Multiply(a, b)
  {

return a*b;

  }

var c = Multiply(5,2);

<p id=demo>

</p>

document.getElementById(demo).innerHTML=c;

```

[AngularJS]: <http://angularjs.org>
[Ace Editor]: <http://ace.ajax.org>
[markdown-it]: <https://github.com/markdown-it/markdown-it>
[Express]: <http://expressjs.com>
[@tjholowaychuk]: <http://twitter.com/tjholowaychuk> 
[jquery]: <http://jquery.com>



[dill]: <https://github.com/joemccann/dillinger>