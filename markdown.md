---
description: Markdown help for formatting text, adding images, creating code blocks
  and more.
title: Markdown help
---
# Text formatting

Example | Description
-------|-------
\*\*bold\*\* | Make text **bold**
\_italic\_ | Make text _italic_

# Links

```
[Link text](https://example.org)
```

> [Link text](https://example.org)	

You can link to other pages in your repo:

```
[Get started](get_started.md)
```

> [Get started](get_started.md)

If the linked page does not exist, the link will be colored red:

```
[Link to a page that doesn't exist](does_not_exist.md)
```

> [Link to a page that doesn't exist](does_not_exist.md)

# Code blocks

~~~
```java
package foo;

public class Foo {
    void bar() {
        System.out.println("Hello, World");
    }
}
```
~~~

or

```
~~~java
package foo;

public class Foo {
    void bar() {
        System.out.println("Hello, World"); 
    }
}
~~~
```

# Web requests

```
$ curl -X POST -H 'Content-Type: application/json' -d '{ "Hello": "World" }' \
  https://example.org
```

Turns into an interactive widget with code examples:

$ curl -X POST -H 'Content-Type: application/json' -d '{ "Hello": "World" }' https://example.org

# Images
	
```markdown
![Alt text](image.png)
```

# Admonitions

Syntax:

```markdown
!!! <type> ["<title>"]
```

Example:

```markdown
!!! info
    Hello, World!
```

Renders:

!!! info
    Hello, World!

[Reads more here](https://github.com/vsch/flexmark-java/wiki/Admonition-Extension)