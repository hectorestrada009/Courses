<!-- Headings (Encabezados) -->

# Curso de Markdown: Titulo h1
## Titulo h2
### Titulo h3
#### Titulo h4
##### Titulo h5
###### Titulo h6

---

<!-- Fonts (Tipos de letra) -->

<!-- Texto en italica -->
*This is an italic text*

<!-- Texto en negritas -->
**This is a strong text**

<!-- Texto tachado -->
~~This is a strikethrough text~~

---

<!-- Unordered lists (Listas desordenadas) -->

* Apple
    * Eat an apple
* Orange

<!-- Ordered lists (Listas ordenadas) -->

1. Apple
    1. Apple 2
2. Orange

---

<!-- Links (Enlaces) -->

[RegStast.com](https://www.regstast.com)

<!-- Cambia el titulo cuando posicionas el cursor sobre la url -->

[RegStast.com](https://www.regstast.com "Custom title")

---

<!-- Quotes (Citas) -->

> This is a quote

<!-- Dividers (Lineas separadoras) -->

---
___

<!-- Como colocar codigo -->

`
Console.log(Hello World);
`

```php
public function index(){
            unset($_SESSION['user_data_credentials']);
            if($this->autenticate()){
                $this->view('pages/home');
            } else {
                $this->view('pages/auth');
            }
        }
```

```python
print("Hello World")
```
---

<!-- Tablas -->

# Base de datos

| Campo     |Tipo de dato    |A/I            |
|-----------|----------------|---------------|
| user_id   | INT            | AUTO_INCREMENT|
| email     | VARCHAR(200)   |               |
| contrase;a| VARCHAR(20)    |               |

---

<!-- Images (Imagenes) -->

![Manjaro logo](Images/Manjaro_logo_text.png "Manjaro Logo")

<!-- GitHub MarkDown (Reglas que solo nos provee GitHub) -->

* [x] Task 1
* [] Task 2
* [] Task 3
* [] Task 4
