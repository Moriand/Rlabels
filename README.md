# Rlabels
Libreria JLutils para etiquetas en ggplot
Descargue estos dos ficheros `stat_fill_labels.R` y `inv_cumsum.R` para despues incluirlo en nuestro proyecto R, recuerde que
estos ficheros deben estar ubicados en su carpeta compartida con R (si no lo sabe use **`getwd()`**) :

```r
source(file = "stat_fill_labels.R")
source(file = "inv_cumsum.R")
```

Una vez ejecutado el anterior, por ejemplo use ggplot:

```r
ggplot(data=casos,aes(x=w,fill=label,weight=prop)) + stat_fill_labels()
```

La libreria no es de mi auditoria, pertenece a larmarange, para mas información sobre su documentación visite

[documentación](http://larmarange.github.io/JLutils/reference/stat_fill_labels.html)
