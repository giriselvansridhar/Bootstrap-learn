# Bootstrap


Defination: __It is a  CSS framework used to simplify the CSS.__ 

---

### 1.SET UP

* Extension: **Live Server**


#### CDN Links: (To insert in the html to install bootstrap in the html )
```

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">


```

```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>


```

### 2. Container
Types:  

* fixed width


```

<div class="container">

</div>
```







* full width


```

<div class="container-fluid">

</div>
```


### 3.Typography


```
<p class="h1"></p>
<p class="h2"></p>
<p class="h3"></p>
<p class="h4"></p>
<p class="h5"></p>
<p class="h6"></p>

```
```

<p class="display-1">Display Heading</p>
```
      

### 4. Text Colors:



```
<p class="text-muted">The Text is muted</p>


```

```
tex-primary
text-success
text-info
text-warning
text-danger
text-secondary
text-white bg-dark
text-dark
text-light bg-dark
```

### 5. Background color

```
bg-primary
bg-success
bg-danger
bg-warning
```


### 6. Rows and Columns (Grid System)

Container  

* Fixed Width (fixed width)
* Full Width  (Automatically change)


Everything should be kept in container  


max_col=12

1*12,2*6,3*4  


```
<div class="conatiner">

<div class="row">
    <div class="col">
        <p>This is a simple column in row</p>
    </div>

    <div>
        <p>This is a simple column in a column</p>
    </div>


</div>
</div>

```

### 7. Blog Layout


```
<div class="row">

<div class="col"></div>
</div>

<header>

<div class="row">

<div class="col">

<h1></h1>
</div>

<div class="col">

<nav>

<ul class='list-inline'>

<li clas="list-inline-item"><a href="#"></a></li>


<ul>
</nav>

</div>
</header>




<footer>
</footer>




```

### 8. Paddling



1. Container give space between each sides.
2. So, Footer and header can be placed outside of the container.

Paddling allarunf all the element

```
p-2

```

There is paddling from p 0-5


Spacing in the x axis
```
px-5
```

Spacing in the y axis
```
py-5
```


Spacing right 
```
ps-3
```
spacing Left

```
pe-3
```

Spacing Top
```
pt-3
```

spacing botttom

```
pb-3
```

### 9.Marigin



|Paddling|Marigin|
|-----|-----|
|Inner Space|Outer Space|




