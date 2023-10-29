



```
r language breast-lobular-carcinoma, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis Meme Lobüler Karsinom TR, echo = (language == "TR")
## breast-lobular-carcinoma - Meme Lobüler Karsinom {#sec-breast-lobular-carcinoma }
```


```
asis Breast Lobular Carcinoma EN, echo = (language == "EN")
## breast-lobular-carcinoma - Breast Lobular Carcinoma {#sec-breast-lobular-carcinoma }
```






```
r breast-lobular-carcinoma screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_breast-lobular-carcinoma-HE.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html",
  file = "./screenshots/thumbnail_breast-lobular-carcinoma-HE.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html](https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html)





```
asis, echo = (language == "TR")

**Meme Lobüler Karsinom**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_breast-lobular-carcinoma-HE.png){width="25%"}](https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html)
```

```
asis, echo = (language == "EN")

**Breast Lobular Carcinoma**

[![Click for Full Screen WSI](./screenshots/thumbnail_breast-lobular-carcinoma-HE.png){width="25%"}](https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/breast-lobular-carcinoma/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

Meme Lobüler Karsinom

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

Breast Lobular Carcinoma

:::

```









:::::








