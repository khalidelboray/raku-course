---
title: Embedded comments
---

{% include menu.html %}

Embedded, or inline comments, have the same form as multi-line comments with the only difference that you place it between other parts of the program. For example:

```raku
my $name;
$name = #`[User input expected here] prompt 'What is your name? ';
say $name;
```

A good syntax highlighter helps a lot to visualize the comments.

{% include nav.html %}
