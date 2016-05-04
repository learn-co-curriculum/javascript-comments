JavaScript Comments
---

## Objectives

- Explain comments in programming languages
- Use the two kinds of JavaScript comments

## What is a comment?

When programming, it's often useful to be able to document what we're thinking — maybe for someone else who might read the code, or just for ourselves later. We don't necessarily want this documentation to run or influence the code in any way, but we want to add some notes _right next to the code_ for safe keeping. This is where comments come in.

## Comments in JavaScript

JavaScript supports two ways of demarcating comments: `//` and `/**/`.

### `//`

`//` makes everything following it _on the same line_ into a comment.

``` javascript
// I'm a comment!
But I'm no longer a comment (and will cause an error)!
```

`//` is useful for short notes. It's good practice to give a comment its own line, even though the following is perfectly valid:

``` javascript
1 + 2 // nothing before the `//` is a comment, so it will run; but this comment is just fine -- by the way, the answer is 3
```

### `/**/`

You might notice a beautiful symmetry with this comment mark — and indeed, it splits nicely in two. The first half, `/*` tells us where the _comment block_ starts; the second half `*/` tells us that it's ended.

```javascript
/*
 I'm a comment, because I'm inside `/*`.
 Still a comment.
 Let's end this comment at the end of this line */

 No longer a comment!
```

As you can see, we can do whatever we want between `/*` and `*/`. This kind of multi-line comment is useful for longer notes, documentation, etc.

Note that you can still use `/**/` on just one line:

``` javascript
/* I'm a comment */

I'm not a comment
```

In this case, it's up to you whether `/**/` or `//` makes more sense.
