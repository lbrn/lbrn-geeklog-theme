**This is a modern theme for Geeklog CMS by Taylor Lapeyre, based on *Denim* by Yoshinori Tahara.**

This theme was built for the website of the *Louisiana Biomedical Research Network*, and has code that is explicitly for this network. For the moment, this is *not* a general Geeklog theme.
A beta version of the site can be found [here](http://test.lbrn.lsu.edu/).

This theme uses the following frameworks and services:
  - [Bootstrap](http://twitter.github.com/bootstrap/)
  - [bootstrap-wysihtml](https://github.com/jhollingworth/bootstrap-wysihtml5/)
  - [Symbolset](https://symbolset.com/)

The basic structure of the theme goes something like this:

    header.thtml:
      <header>
      <nav>

    leftblocks.thtml:
      <div.hero-unit>

    centerblocks, etc.thml:
      <div.span9>
        <article.row>
        ...

    footer.thtml:
      rightblocks.thtml:
      <div#sidebar.span3>
        <ul.nav-list>
         ...
      <footer>
