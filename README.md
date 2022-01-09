Here we can observe an event bubbling up on 

```sql
    <section onclick="alert('section clicked')">
        <p onclick="alert('paragraph clicked')">
            I am a paragraph:
            <button onclick="alert('button clicked')">Click</button>
        </p>
    </section>
```

While on 

```sql
    <div id="container">
        Click To Hide
        <button id="changeColor">Change Color</button>
    </div>
 ```

 bubbling was stopped using

 ```sql
.stopPropagation();
 ```
##
## [Click for the dev tools console](https://verson-tech.github.io/Bubbling/)