# From Words to Pictures: Text Analysis and Visualization #

**Speaker**: Nicholas Diakopoulos, University of Maryland

## What's different about text? ##

Text is a sequence of written or spoken words, but it can be analyzed
in other forms:

* Frequencies/rates
* Context
* Semantics

This differs from other kinds of data structures:

* Tables
* Geometries (2D or 3D)
* Networks (graphs)
* Trees (hierarchies)
* Time series

## Stuff about presidents ##

Examples include [presidential pronouns](http://www.buzzfeed.com/johntemplon/obamas-pronouns-dont-make-him-narcissist)
and the [State of the Union semantics](http://www.washingtonpost.com/wp-srv/special/politics/2014-state-of-the-union/language-of-sotu/).

Twitter also created [an SOTU streamgraph](http://twitter.github.io/interactive/sotu2015/).
Some of the best visualizations of text let people approach the text from
different directions, like this one does. Try to extract a variety of metrics
from the source document where possible.

## Networks and associations ##

"Colocation networks" show what concepts appear together, especially in a large
corpus (collection; plural is "corpora") of text.

In a similar vein, [Ben Schmidt](http://benschmidt.org/profGender/) analyzed
language in professor reviews based on the genders of the professors being
reviewed.

[Jerome Cukier](http://www.jeromecukier.net/projects/agot/events.html) worked
on a less journalistic project with some of these concepts: Events in Game of
Thrones over time.

## Word clouds ##

Word clouds get a bad rap, but they can be done well when they provide context.
An example is [NYT's 2012 Republican National Convention coverage](http://www.nytimes.com/interactive/2012/08/28/us/politics/convention-word-counts.html?_r=0).

Diakopoulos refers to this as KWIC (keyword in context) and highly recommends
this method for non-word-cloud things as well.

There's also an approach known as the "compare cloud", which is sort of a
mashup of the word cloud and the Venn diagram. [Here's one.](http://nad.webfactional.com/lingoscope/v2/)

[Word trees](http://www.jasondavies.com/wordtree) are another contextual
visualization type that might come in handy.

## Text understanding ##

Visualize what the text is **about**, not just what the text **says**.

This obviously is in rather experimental stages at this point, such as
[NewsViews](http://www.nickdiakopoulos.com/wp-content/uploads/2011/07/NewsViews_20140112_CR.pdf)
and [Timeline Curator](http://www.cs.ubc.ca/group/infovis/software/TimeLineCurator/),
but there seems to be a lot of potential.
