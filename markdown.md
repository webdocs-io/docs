---
title: Markdown help

---
## Text formatting

Example | Description
-------|-------
\*\*bold\*\* | Make text **bold**
\_italic\_ | Make text _italic_

## Links

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

## Code blocks

~~~java
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

```java
~~~java
package foo;

public class Foo {
    void bar() {
        System.out.println("Hello, World"); 
    }
}
~~~
```

## Images

```markdown
![Alt text](image.png)
```	