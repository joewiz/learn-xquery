# Learn XQuery: A list of great articles, blog posts, and books for learning XQuery

Let's show the world how to learn XQuery. Pull requests welcome. Quality over comprehensiveness - just the best, most helpful resources, please. Talk about [`#learnxquery`](https://twitter.com/search?q=learnxquery) on Twitter.

Also, check out these [resources powered by XQuery](https://github.com/joewiz/xquerypower), [repositories with XQuery on GitHub](https://github.com/search?utf8=%E2%9C%93&q=language%3AXQuery&type=Repositories&ref=searchresults), and [questions about XQuery on Stack Overflow](http://stackoverflow.com/questions/tagged/xquery).

## Gentle introductions

- [W3Schools XQuery](http://www.w3schools.com/xquery/). Limited to XQuery 1.0, but a quick overview.
- [XQuery Wikibook Beginning Examples](http://en.wikibooks.org/wiki/XQuery#Beginning_Examples). Perhaps the best developed portion of the XQuery Wikibook site (see remarks below).

## In depth introductions

Some people can learn languages by reading online tutorials. Some people like to dive into a book, or have one on their shelf for reference.

- [XQuery: Search across a variety of XML Data](http://shop.oreilly.com/product/9780596006341.do), Priscilla Walmsley, O'Reilly 2007. The standard text for XQuery 1.0. Also introduces [functx](http://www.xqueryfunctions.com/). Doesn't cover the topic of building applications with XQuery; this is out of scope.
- [eXist: A NoSQL Document Database and Application Platform](http://shop.oreilly.com/product/0636920026525.do), Erik Siegel and Adam Retter, 2014. If Walmsley limits herself to the language, Siegel and Retter coherently introduce approaches to building applications with one popular XQuery-based platform, eXist. Example code for the book is [on GitHub](https://github.com/eXist-book/book-code).

## The specs

- 1.0 (W3C Recommendation): [XQuery 1.0](http://www.w3.org/TR/xquery/), [Data Model](http://www.w3.org/TR/xpath-datamodel/), [Functions and Operators](http://www.w3.org/TR/xquery-operators/), [Serialization](http://www.w3.org/TR/xslt-xquery-serialization/), [Update Facility](http://www.w3.org/TR/2011/REC-xquery-update-10-20110317/).
- 3.0 (W3C Recommendation): [XQuery 3.0](http://www.w3.org/TR/xquery-30/), [Data Model](http://www.w3.org/TR/xpath-datamodel-30/), [Functions and Operators](http://www.w3.org/TR/xpath-functions-30/), [Serialization](http://www.w3.org/TR/xslt-xquery-serialization-3/), [Update Facility](http://www.w3.org/TR/xquery-update-30/)
- 3.1 (W3C Candidate Recommendation): [XQuery 3.1](http://www.w3.org/TR/xquery-3/), [Data Model](http://www.w3.org/TR/xpath-datamodel-31/), [Functions and Operators](http://www.w3.org/TR/xpath-functions-31/), [Serialization](http://www.w3.org/TR/xslt-xquery-serialization-31/), Update Facility (no 3.1 version yet; see the 3.0 version).

## Latest developments in XQuery

- [New in XQuery 3.1: Maps and arrays](http://goxrxyourself.com/2015/04/13/new-in-xquery-3-1-maps-and-arrays/), Jesse Alama, 2015. A core new set of features in XQuery 3.1.
- [A preview of XQuery 3.1's JSON support in eXist](http://joewiz.org/2015/01/18/a-preview-of-xquery-3.1s-json-support-in-exist/), Joe Wicentowski, 2015. Shows how XQuery 3.1 improves JSON handling.

## More tutorials and thought pieces

- [XQuery Wikibook](http://en.wikibooks.org/wiki/XQuery): An introduction to XQuery and a cookbook for various applications. Fairly eXist-centric and many pages out of date, but very useful still.
- [XQuery and Lazy Enrichment](http://xquery.typepad.com/xquery/2007/08/xquery-and-lazy.html), Matt Turner, 2007. Demonstrates a simple but powerful technique for enriching text with links to Wikipedia. Easily applied to any XQuery implementation.
- [MarkLogic Server and Office 2007](https://developer.marklogic.com/blog/smallchanges/2009-01-22), Pete Aven, 2007-09. The last in a series (see the links to the other articles at the bottom) on how to open, manipulate, and create Microsoft Office documents using XQuery. Easily applied to any XQuery implementation.
- [XQuery, the Server Language](http://www.xml.com/pub/a/2007/06/01/xquery-the-server-language.html), Kurt Cagle, 2007. Explains that XQuery is much more than a language for querying XML.
- [XQuery Novelties Revisited](http://grtjn.blogspot.nl/2011/10/xquery-novelties-revisited.html), Geert Josten, 2011. Situates XQuery among the various XML and non-XML standards. Provides a little history on the development of XQuery.
- [XQuery: It's not just for queries!](http://goxrxyourself.com/2015/04/29/xquery-its-not-just-for-queries/), Jesse Alama, 2015. Emphasizes wide utility of XQuery.

## Documentation from XQuery implementations about their use of XQuery

In depth articles on conformance to / divergence from the spec, and links to key articles and documentation:

- [XQuery in BaseX](http://docs.basex.org/wiki/XQuery). See also [all BaseX documentation](http://docs.basex.org/wiki/Main_Page).
- [XQuery in eXist-db](http://exist-db.org/exist/apps/doc/xquery.xml). See also [eXist XQuery Features Demo](http://exist-db.org/exist/apps/demo/index.html), [XQuery Function Documentation](http://exist-db.org/exist/apps/fundocs/index.html), [Getting Started with Web Application Development in eXist](http://exist-db.org/exist/apps/doc/development-starter.xml) and [all eXist documentation](http://exist-db.org/exist/apps/doc/documentation.xml) 
- [XQuery in MarkLogic](https://docs.marklogic.com/guide/xquery). See also [Application Developer's Guide](https://docs.marklogic.com/guide/app-dev) and [all MarkLogic documentation](https://docs.marklogic.com/)

## Mailing lists, forums

- XQuery-Talk: a mailing list best for general XQuery questions and discussion. [Subscribe](http://x-query.com/mailman/listinfo/talk). [Archives](http://x-query.markmail.org/).
- [Stack Overflow](http://stackoverflow.com/questions/tagged/xquery) has many active users who answer XQuery questions.
- Implementation mailing lists: 
    - BaseX-talk: [Subscribe](https://mailman.uni-konstanz.de/mailman/listinfo/basex-talk). [Archives](https://mailman.uni-konstanz.de/pipermail/basex-talk/).
    - eXist-open: [Subscribe](https://lists.sourceforge.net/lists/listinfo/exist-open). [Archives](http://exist-open.markmail.org/).
    - MarkLogic-developer: [Subscribe](https://developer.marklogic.com/mailman/listinfo/general). [Archives](http://marklogic.markmail.org/).
