---
title: "My Article Name – Тест"
slug: "my-article-name"
categories: ["Academic"]
tags: ["Blog"]

date: 2020-05-19T16:31:46+03:00
lastmod: 2020-05-19T16:31:46+03:00
featured: false
draft: false
math: true
diagram: true


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 1
  caption: "caption: Image by [Rachel Martin](https://unsplash.com/photos/PnAc2UaeqII)"
  focal_point: ""
  preview_only: true #false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
resources:
- name: "featured-image"
  src: "featured.png"

---

Проверка Шахматных Диаграмм
<!--more-->
![Диаграмма](https://www.dmitriev.ee/punbb/extensions/chess_diagram/gendiag-jane.php?coord&size=29&style=merida&fen=r1bq1rk1/p1p2pb1/1p1p3p/2nPp1p1/2P1P3/2NB1NP1/PP2QPP1/R3R1K1+w+-+-+0+15)
**FEN**: `r1bq1rk1/p1p2pb1/1p1p3p/2nPp1p1/2P1P3/2NB1NP1/PP2QPP1/R3R1K1`

Картинка
![Диаграмма2](https://www.dmitriev.ee/punbb/extensions/chess_diagram/gendiag-fritz.php?size=29&coord&style=alfa&fen=r6b/p1pq1p1k/1p2p1rp/4PpBQ/3P1P2/2PR2R1/P5PP/6K1)
**FEN:** `r6b/p1pq1p1k/1p2p1rp/4PpBQ/3P1P2/2PR2R1/P5PP/6K1`

![Диаграмма3](http://www.euruchess.org/diagol/29/diagol.php?position=r1bq1rk1/p1p2pb1/1p1p3p/2nPp1p1/2P1P3/2NB1NP1/PP2QPP1/R3R1K1%20w%20-%20-%200%2015)
**FEN**: `r1bq1rk1/p1p2pb1/1p1p3p/2nPp1p1/2P1P3/2NB1NP1/PP2QPP1/R3R1K1`
![Диаграмма3](https://www.dmitriev.ee/punbb/extensions/cd52/gendiag.php?size=29&coord&style=alfa&fen=r6b/p1pq1p1k/1p2p1rp/4PpBQ/3P1P2/2PR2R1/P5PP/6K1)

<center>Centered text</center>

An example **flowchart**:

    ```mermaid
    graph TD
    A[Толик] -->|Плюс| B(Вовик)
    B --> C{Родные Братья}
    C -->|Один| D[Стрёмберг]
    C -->|Другой| E[Дмитриев]
    ```

renders as

```mermaid
graph TD
A[Толик] -->|Плюс| B(Вовик)
B --> C{Родные Братья}
C -->|Один| D[Стрёмберг]
C -->|Другой| E[Дмитриев]
```

### Diagrams

Academic supports a Markdown extension for diagrams. You can enable this feature by toggling the `diagram` option in your `config/_default/params.toml` file or by adding `diagram: true` to your page front matter.

An example **flowchart**:

    ```mermaid
    graph TD
    A[Hard] -->|Text| B(Round)
    B --> C{Decision}
    C -->|One| D[Result 1]
    C -->|Two| E[Result 2]
    ```

renders as

```mermaid
graph TD
A[Hard] -->|Text| B(Round)
B --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

An example **sequence diagram**:

    ```mermaid
    sequenceDiagram
    Alice->>John: Hello John, how are you?
    loop Healthcheck
    John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
    ```

renders as

```mermaid
sequenceDiagram
Alice->>John: Hello John, how are you?
loop Healthcheck
John->>John: Fight against hypochondria
end
Note right of John: Rational thoughts!
John-->>Alice: Great!
John->>Bob: How about you?
Bob-->>John: Jolly good!
```

    ```mermaid
    pie title NETFLIX
    "Time spent looking for movie" : 90
    "Time spent watching it" : 10
    ```

```mermaid
pie title NETFLIX
"Time spent looking for movie" : 90
"Time spent watching it" : 10
```
