# Tragicomique Theme

The **Tragicomique** Theme for [Grav CMS](http://github.com/getgrav/grav) is a simple webcomic-ready theme.

---

## Usage

To set up a webcomic all you need is a simple file structure and naming convention. 

- Create a folder for your comic and name the markdown file within `comic.md`. All you need inside this file is a title/frontmater, such as  

```yaml
title: My Cool Comic
```

- Create a subfolder for each page of your comic, and name their markdown files `page.md`. Again, place a title in the frontmater, and add the comic image file to the folder.
- That's it! You're done. Keep adding as many folders and pages as you need!

Your grav pages folder structure will look something like this, a name in square `[]` denotes a folder:

```
[pages]
  [01.thebegining]
    comic.md
    [01.page1]
      comic01-01.jpg
    [02.page2]
      comic01-02.jpg
    [03.page3]
      comic01-02.jpg
  [02.chapter2]
    comic.md
    [01.page1]
      comic02-01.jpg
    [02.page1]
      comic02-02.jpg

```