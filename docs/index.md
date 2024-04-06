---
hide: [navigation]
status: new
---

# Welcome to APIGo2Doc: Simplifying API Documentation

![doc-image](https://rickey-alok.github.io/api-go-to-doc/img/home_page_img.png)

`API-Go2Doc` portal is a reference guide that one can turn to for information and guidance on topics related to API Documentation only. It aims to present information in a simple, easy-to-understand language. Just straightforward concepts at one place - no more husstle.

When we talk about the API documentation, we often hear the term `Docs-as-Code` approach. This approach involves creating documentation using the same tools and processes that developers use for coding. So, to be in the shoes of a developers, you must familiarize yourself with the topics below:

- **Visual Studio Code (VS Code)**: A versatile code editor that developers love
- **Git & GitHub**: Essential for version control and collaborative development

- **Postman**: Simplify API testing and collaboration.

One of the best things is that no need to spend a single penny to access these software tools as they are all open-source 😁.

# Key Topics for API Documentation

As you embark on this journey, consider exploring the following topics. But before delving into these topics, let’s start with the basics: What is an API? It’s a fundamental question that sets the stage for your exploration.

[Markdown ](./API%20Docs/Markdown.md){ .md-button }
[OpenAPI Specification](./API%20Docs/OepnAPISpec.md){ .md-button }
[cURL](./API%20Docs/cURL.md){ .md-button }
[JSON](./API%20Docs/JSON.md){ .md-button }

---

[: fontawesome-solid-paper-plane](#){ .md-button }

---

## Grouping code blocks

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

---

## Grouping other content

=== "Unordered list"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

=== "Ordered list"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

---

## Embedded content

!!! example

    === "Unordered List"

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

    === "Ordered List"

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```

---

## Using annotations

Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
{ .annotate }

1.  :man_raising_hand: I'm an annotation! I can contain `code`, **formatted
    text**, images, ... basically anything that can be expressed in Markdown.
