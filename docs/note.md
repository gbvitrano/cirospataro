# Note varie
Pagina di appunti per capire impostazioni di configurazione del progetto di documentazione

## Annotation in code block (annotazioni mel blocco del codice)

[https://squidfunk.github.io/mkdocs-material/reference/code-blocks/#adding-a-title](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/#adding-a-title)


``` yaml
theme:
  features:
    - content.code.annotate # (1)
```

(1).  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.



## Adding a title in code block

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```


## Add announcement
![](https://user-images.githubusercontent.com/3757525/139603760-edc4a47f-b19e-4be7-b684-633cf4c4cebc.png)

Il seguente codice è posizionato nel file `docs/override/main.html`

```
<!-- Add announcement here, including arbitrary HTML 
(https://squidfunk.github.io/mkdocs-material/setup/setting-up-the-header/#announcement-bar) -->

{% block announce %}
<span style="background-color: #f50505; color: #ffffff; padding: 0px 3px; border-radius: 4px;"><b>Importante news</b>:</span> questa è una <strong><span style="color: #ff0000;">prova</span></strong> di announcement nell'header sopra il titolo, ed è posizionata dal rigo 5 a 8 del file <code> main.html </code> 
{% endblock %}
```
