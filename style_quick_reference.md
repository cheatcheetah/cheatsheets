---
title: Cheatsheet's elements introduction
category: help
intro: |
  A quick reference of styles available for your cheat sheets.
keywords:
  - Help
  - Cheat sheet style
  - Cheat sheet styling
---

This cheat sheet contains examples of how differents markdown tags are rendered. For instance this is a regular text, not nested inside any headers tag.

You can see the source of the markdown used to generate this page [on Github](https://github.com/cheatcheetah/cheatsheets/blob/main/style_quick_reference.md).

# I am a `h1` tag

This is how a paragraph inside an `h1` section is displayed.

If you slide your mouse on the title above, you'll see that you can copy a link to that section by clicking on it.

## I'm a `h2` tag
{: .-three-column}

Some text inside `h2`.

Note that this `h2` has the `{: .-three-column}` options set: if your screen is large enough, the `h3` tags below should be displayed in 3 columns.

### I'm a `h3` tag

And I'm some text inside a `h3`. As you can see, everything inside an `h3` is displayed inside a container.

### Hey I'm a `h3` too!

Inside `h3`s, the main options are the following.

You can display lists:

- Some ...
- ... list ...
- ... elements!

Or some code:

```text
Some code
```

Finally, note that [links](#im-a-h2) are supported too.

### ... and me too!

#### I'm an `h4`

You can see that `h4`s are not rendered as containers, but as `p` tags with emphasis.

And that's all you'll need to create your own cheat sheets!

## Also see
{: .-one-column}

* [Cheat sheet style full reference](https://brew.sh/) _brew.sh_
* [Cheat sheet meta reference](https://docs.brew.sh) _docs.brew.sh_
{: .-also-see}
