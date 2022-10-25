## Hi, I'm Sara 👩🏽‍💻
<!-- <div>
    <div>
        <p align="center">
            <img src="background.png" width="80%" />
        </p>    
    </div>

    <div>
        <h1>hola</h1>
    </div>
</div> -->
---
output: html_document
---

:::: {style="display: flex;"}

::: {}
Here is the **first** Div.

```{r}
str(iris)
```
:::

::: {}
And this block will be put on the right:

```{r}
plot(iris[, -5])
```
:::

::::