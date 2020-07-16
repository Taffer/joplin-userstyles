# All the Markdown

# Heading 1

## Heading 2

### Heading 3

This is some **bold text**

This is some *italic text*

> Kent.
> Where's the king?

> Gent.
> Contending with the
> fretful elements

* Milk
* Eggs
* Beers
    * Desperados
    * Heineken
* Ham

1. Introduction
2. Main topic
    1. First sub-topic
    2. Second sub-topic
3. Conclusion

This is `someJavaScript()`

Here's some JavaScript code:

```
function hello() {
    alert('hello');
}
```

Language is normally auto-detected,
but it can also be specified:

```sql
SELECT * FROM users;
DELETE FROM sessions;
```

Indent with a tab or 4 spaces
for unformatted text.

    This text will not be formatted:

    Robert'); DROP TABLE students;--

This is detected as a link:

https://joplinapp.org

And this is a link anchoring text content:

[Joplin](https://joplinapp.org)

And this is a link, with a title,
anchoring text content:

[Joplin](https://joplinapp.org "Joplin project page")

![Joplin icon](https://git.io/JenGk)

One rule:
***
Another rule:
---



| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

$$
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

- [ ] Milk
- [ ] Rice
- [ ] Eggs

==marked==

Simples inline footnote ^[I'm inline!]

[toc]

X~1~

X^2^

Term 1

:   Definition 1

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

*[HTML]: Hyper Text Markup Language
The HTML specification


:smile:

++inserted++

Multimarkdown table:

|             |          Grouping           ||
First Header  | Second Header | Third Header |
 ------------ | :-----------: | -----------: |
Content       |          *Long Cell*        ||
Content       |   **Cell**    |         Cell |

New section   |     More      |         Data |
And more      | With an escaped '\|'         ||
[Prototype table]
