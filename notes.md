
<!-- Six types of headings in markdown language -->

# Heading 1

<!-- ## Heading 2

### Heading 3

#### Heading 4

#### Heading 5

##### Heading 6 -->

<!-- This is comment -->

<!-- Paragraph -->

## Paragraph

This is line 1
This is line 2

This is line 4  <!-- In order to change lines -->  
This is line 5  <!-- add two whitespaces after first line -->
                <!-- Or use <br> tag -->

## Lists

### Unordered List

* Element 1

+ Element 2   <!-- you can use any operator for unorderd list -->

- Element 3

<!-- generate horzontal line using 3 dash -->

---  

### Orderd List

1. Element 1

1. Element 2

1. Element 3

### Nested List

<!-- Incase of UL, use 2 whitespaces before nested element -->

* Element 1
  * Nested Element 1
    * Nested Nested Element 1
  * Nested Element 2

* Element 2
  1. Nested Element

<!-- Incase of OL, use 3 whitespaces before nested element -->

1. Element 1
   1. Nested Element 1
      1. Nested Nested Element 1
   1. Nested Element 2

### HTML Tags

<!-- Markdown also has support for html tags -->

<h1>Heading</h1>
<p>Paragraph</p>

<!-- You can use backticks to include html tags -->

`<h1>Heading</h1>`  
`<p>Paragraph</p>`

### Links

[Click Here](https://google.com)

<!-- To include tooltip -->

[Click Here](https://google.com "google")

### Images

![Pikachu](./pikachu.png "pikachu")

### Images with Links

[![Pikachu](./pikachu.png)](https://pokemon.com "www.pokemon.com")

### Blockquotes

>This is blockquote  
>This is line 2
>  
>1. Item 1
>
>2. Item 2
>
>    * Nested Item
>      * Nested Nestd Item
>
>>This is nested blockquote
>>
>> * Item 1
>>
>> 1. Item 2
>>
>>>This is nested nested blockquote
>>>
>>Back again  
>>
>back again

### Tables

|   First Name |   Last Name    |
|   :----------: |   :----------:   |  
|   Hamza      |    Ahmed       |
|   Osama      |    Khan        |
|   Fazal      |    Ahad        |

<!-- Add colons in line 121 at beginning to left align -->
<!-- Add colons in line 121 at end to right align -->
<!-- Add colons in line 121 at beginning and end to center align -->
<!-- you can easily create tables by searching for markdown table generator on google -->

### Using Markdown Keywords

<!-- Use markdown keywords by using escape character -->

\# Heading  
\* List

### Display Code

<!-- you can highlight your code by writing the name of programming language -->
```python
  def add(a, b):
      return (a+b)  
```

```js
  const add = (a,b) => a+b;
  add(2,3)
```
