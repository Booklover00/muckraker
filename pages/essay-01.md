---
title: Essay 1
layout: about
permalink: /essay-01.html
---
{% include feature/image.html filename="sotu-word-cloud.png" alt="word cloud generated from state of the union addresses." %} 

{% include feature/nav-menu.html sections=""Introduction;My First Subheading;Conclusion;Note" %}

# Muckrakers


{% include feature/line-chart.html data="sotu-20th-century" topic="Patriotism and Nationalism" %}

I named this graph patriotism and nationalism, and I thought it was interesting because it shows a steady decline over time. [^1]

---


[GitHub Help](https://help.github.com/){:target="_blank" rel="noopener"}
## Introduction

### My First Subheading

There were many famous muckrakers that worked to expose corruption.
Each one wrote many articles and were very brave to take on the corrupt elites.

Leave an empty line between headings and paragraphs.

*Journalists* or **Muckrakers**.

Citing your work is important! [^1]

Title sections of your essay with headings, by adding a pound sign (`#`) in front of the title:

# Heading One

## Notes

[^1]: John D’Agata, ed., *The Making of the American Essay* (Minneapolis: Graywolf Press, 2016), 19–20.

### Heading Three, etc.

Hyperlinks look like this [GitHub Help](https://help.github.com/).

A bullet list is created using `*`, `+`, or `-`, like:

- dog
- cat
- muffin

A numbered list is created using a number + `.`, like:

1. one
2. two
6. three
2. four

A horizontal line break can be useful for separating content:

----

Include an image:

{% include feature/image.html filename="demo_001.jpg" alt="image of UI Admin building" caption="Historic photo of the University of Idaho campus" width="50" %}

Include a pdf:

{% include feature/pdf.html filename="demo_002.pdf" caption="Historic postcard" width="50" %}

## Conclusion

More documentation on how to write your essay in Markdown--as well as how to include images, pdfs, and topic visualizations--can be found at <https://learn-static.github.io/hist-320/topic-modeling.html>.

## Notes

[^1]: Katie Kitamura, A Separation (New York: Riverhead Books, 2017), 25.
