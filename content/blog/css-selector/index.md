---
title: CSS Selectors
date: "2021-01-20T22:40:32.169Z"
# description: This is a custom description for SEO and Open Graph purposes, rather than the default generated excerpt. Simply add a description field to the frontmatter.
---

CSS selectors are used to select the content you want to style. Selectors are the part of CSS rule set. CSS selectors select HTML elements according to its id, class, type, attribute etc .

## There are several different types of selectors in CSS:

1. CSS Element Selectors
2. CSS ID Selectors
3. CSS Class Selectors
4. CSS Universal Selectors
5. CSS Group Selectors
6. CSS Pseudo-classes Selectors
7. CSS Pseudo-elements Selectors
8. CSS Attribute Selectors

#### 1.CSS Element Selectors

The elemnt selector selects the HTML element by name.

      Example
      Here all <p> elements on the page will be center-aligned with red
      text color:
      p{
      text-align: center;
      color: red;
       }

#### 2. CSS ID Selectors

The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unique within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

      Example
      The CSS rule below will be applied to the HTML element with id="idSelector":
      #idSelector {
      text-align: center;
      color: red;
      }

#### 3. CSS Class Selectors

The class selector selects HTML elements with a specific class attribute. It is used with a period character . (full stop symbol) followed by the class name.

      Example
      In this example all HTML elements with class="classSelector" will be red and center-aligned:
      .classSelector {
       text-align: center;
       color: red;
       }

#### 4. CSS Universal Selector

The universal selector (\*) selects all HTML elements on the page.

        Example
        The CSS rule below will affect every HTML element on the page:

       * {
       text-align: center;
       color: blue;
        }

#### 5. CSS Group Selector

The grouping selector selects all the HTML elements with the same style definitions.

        Example
        In this example we have grouped the selectors with same style definitions:
        h1, h2, p {
        text-align: center;
        color: red;
        }

#### CSS Pseudo-classes Selectors

A pseudo-class is used to define a special state of an element.
For example, it can be used to:

1.  Style an element when a user mouses over it .
2.  Style visited and unvisited links differently .
3.  Style an element when it gets focus

Syntax

The syntax of pseudo-classes:

              selector:pseudo-class {
              property: value;
              }

Example
The example of pseudo-classes:

           selector:hover {
           color: blue;
            }

#### CSS Pseudo-elements Selectors

A CSS pseudo-element is used to style specified parts of an element.

For example, it can be used to:

1.  Style the first letter, or line, of an element
2.  Insert content before, or after, the content of an element

example: <p>my name is jyoti pal</p>

        p::my name{
        color:blue;
        }

#### CSS [Attribute] Selectors

The [attribute] selector is used to select elements with a specified attribute.

            syntax
            a[target] {
           property: value;
            }

The following example selects all <a> elements with a target attribute:

        a[href="www.example.com"]{
        color:blue;
        }
