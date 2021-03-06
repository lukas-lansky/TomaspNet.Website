﻿@{ 
  Layout = "paper";
  Title = "Fun with Parallel Monad Comprehensions";
  Description = "";
}

# Fun with Parallel Monad Comprehensions

> Tomas Petricek
>
> In The Monad.Reader Issue 18 (Unreviewed article)
  
Monad comprehensions have an interesting history. They were the first syntactic extension for 
programming with monads. They were implemented in Haskell, but later replaced with plain list
comprehensions and monadic <code>do</code> notation. Now, monad comprehensions are back in Haskell,
more powerful than ever before!

Redesigned monad comprehensions generalize the syntax for working with lists. Quite interestingly, 
they also generalize syntax for zipping, grouping and ordering of lists. This article shows how to 
use some of the new expressive power when working with well-known monads. You'll learn what 
"parallel composition" means for parsers, a poor man's concurrency monad and an evaluation 
order monad.

## Article and more information

 - Download [The Monad.Reader Issue 18](http://themonadreader.files.wordpress.com/2011/07/issue18.pdf), which contains the article (PDF)</li>
 - Download [the article alone (PDF)](comprefun.pdf) or [read it online](http://tomasp.net/blog/comprefun.aspx/)
 - See [the samples from the article](http://github.com/tpetricek/Haskell.Joinads) at Github
   
## <a id="cite">Bibtex</a>
This is an unreviewed article, published in an online electronic magazine about
Haskell. For more information about the magazine, see [The Monad.Reader](http://www.haskell.org/haskellwiki/The_Monad.Reader)
on Haskell wiki. To cite the article, use:

    [lang=tex]
    @@other{comprefun,
      author       = {Petricek, Tomas},
      title        = {{F}un with {P}arallel {M}onad {C}omprehensions},
      howpublished = {Available online in {T}he {M}oand.{R}eader {I}ssue 18},
      year         = {2011},
      url          = {http://tomasp.net/academic/articles/comprefun/comprefun.pdf},
    }

If you have any comments, suggestions or related ideas, I'll be happy to 
hear from you! Send me an email at [tomas.petricek@cl.cam.ac.uk](mailto:tomas.petricek@cl.cam.ac.uk)
or get in touch via Twitter at [@@tomaspetricek](http://twitter.com/tomaspetricek).