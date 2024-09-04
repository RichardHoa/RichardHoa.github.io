---
layout: page
title: Static site generator
description: Static site generator using Python
importance: 2
category: fun
---
## Source code:
Please view the source code [here](https://github.com/RichardHoa/basic-static-site-generator)

## How it works:

This static site generator turns raw markdown code into beautiful HTML pages. Here's an example of how it processes markdown content

## Raw Markdown Code

Below is a sample markdown file that could be used as content for the generator:

```markdown
# Tolkien Fan Club

**I like Tolkien**. Read my [first post here](/majesty)

Read my [test](/test)

> All that is gold does not glitter

## Reasons I like Tolkien

* You can spend years studying the legendarium and still not understand its depths
* It can be enjoyed by children and adults alike
* Disney *didn't ruin it*
* It created an entirely new genre of fantasy

## My favorite characters (in order)

1. Gandalf
2. Bilbo
3. Sam
4. Glorfindel
5. Galadriel
6. Elrond
7. Thorin
8. Sauron
9. Aragorn

Here's what `elflang` looks like (the perfect coding language):

func main(){
    fmt.Println("Hello, World!")
}

```

## HTML page
The markdown above would be transformed into a structured and styled HTML document that looks like this:

{% include figure.liquid loading="eager" path="assets/img/static-site-generator.png" title="example image" class="img-fluid rounded z-depth-1" %}
