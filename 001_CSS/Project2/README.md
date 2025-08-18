## Positions

- Lower it is more important it is
``` 
Example
li {
    color:red;
    color:blue;
}
li {
    color: orange;  // it will applied it is at lower index
}
```

## Specificity

### Specificity defines through diffrent parameters
- element
- class
- attribute
- id

```
Specificity 
here 
1. id means #first-id {color: red} // higher specifity always cascade others
2. attribute p[draggable] {color: green} // second higher priorty
3. class .fist-class {color: yellow} // get lesser priorty because many element have same class
4. element h1 {color: skyblue}  // least specifity 
```

## Type

```
There are three type of style linking

first 
inline     <h1 style="color: red"> Hello </h1>

second 
<style> h1 {color: yellow} </style>

third
<link rel="spreadsheet" href="style.css">

```

### Important Keyword

```
Important is a keyword that is used to forcely 
apply any css property instead of following the pattern of last of specifity

h3 {
    color: red;
    color: blue !important; /* this is way to use important keyword */
    color : green;
}