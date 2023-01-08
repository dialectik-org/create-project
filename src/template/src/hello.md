# Hello Dialectik world!

By default, every markdown file (`.md` extension) is compiled as a standalone resource.

## Bundle several resources

If you want to bundle two markdown files together, you may use the `bundle` option as illustrated below:

```md title="f1.md"
---
bundle : f1_2
---

This is one md file.
Click [here](f2) to access `f2.md`.
```

```md title="f2.md"
---
bundle : f1_2
---

This is another.
Click [here](f1) to access `f1.md`.
```

This will create a bundle with f1 and f2.
