
Open Source Book Builder / Maker / Generator / Compiler from Markdown Manuscripts (in Plain Text) 

# Markdown Tools › Books - Add Your Tool!

Markdown Tools › Books Directory - see it live @ [`mundimark.github.io/markdown-tools-books`](http://mundimark.github.io/markdown-tools-books)


## How-To Add Your Tools

* Fork the [`/markdown-tools-books`](https://github.com/mundimark/markdown-tools-books) repo on GitHub
* Add a new entry in the [`tools.yml`](https://github.com/mundimark/markdown-tools-books/blob/master/tools.yml) file and fill out all fields.
  Example:

``` yaml
- title:     Pandoc
  author:    John MacFarlane et al
  formats:   [html (+epub), latex (pdf)]
  templates: Custom (Pandoc)
  github:    jgm/pandoc
  web:       http://pandoc.org
  language:  Haskell
```  

or

``` yaml
- title:     Octobook (+Jekyll)
  author:    Gerald Bauer et al
  formats:   [html]
  templates: Liquid
  github:    octobook/octobook
  language:  Ruby
```

## Meta

**License**

The markdown book tools directory is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the [wwwmake forum/mailing list](http://groups.google.com/group/wwwmake). Thanks!
