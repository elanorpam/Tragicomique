# Tragicomique Theme

The **Tragicomique** Theme is for [Grav CMS](http://github.com/getgrav/grav) is for webcomics.

---

## Usage

To set up a webcomic you just need a simple file structure and naming convention, create a folder for your comic and name the markdown file within `comic.md` all you need in that file is a title frontmater for example 

```yaml
title: My Cool Comic
```

Then create subfolders for each page of your comic and name their markdown files `page.md` again place a title in the frontmater, add an image file to the folder and your done. Keep adding as many pages as you need!

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