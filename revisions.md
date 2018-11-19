## Reviewer 1

> It would be nice to include a little more detail about what the various
> sites can do and cannot do. For example, rdrr.io searches only for single
> words, many search sites do not say what they search or how to use the
> search box.

I addressed this in a new sentence in the last paragraph of the "Search" section but did not go into detail about individual sites; I don't think that's a good use of space in this paper.

> When people, in the survey, say they learn from other people, this makes
> sense, but SOMEONE has to keep up with new packages. Just to take an
> example, I recommended to someone that they look into Spearman's "tetrad
> difference", and I wanted to find out whether a package existed that would
> report a significance test for this very obscure (and very old)
> statistic. If I had found one - I didn't - I would have then been a
> position to recommend it to others. But this has to start somewhere. A
> related example where I frequently do recommend a package is that I
> discovered, thorough search, the yacca package, which was at the time (and
> may still be) the only package that did canonical correlation and reported
> a significance test for each canonical correlate. So now I am a source of
> recommendations, but it took search to find that.
> 
> Added later: This issue bears on the final conclusion of the paper, about
> meetup groups and individual recommenders. The problem is that someone in
> these groups must be in a position to learn about the capabilities of
> relevant packages, especially new ones.

I added a sentence to the section "Value of personal impact" to make the point the reviewer brings up here, although the huge proportion of folks who are learning about packages from social media, blogs, etc answers his question, I think. We have network effects in our communities. I don't think it impacts the final conclusion and have not changed that.

> I was happy to see in the survey data that my own search site gets very
> little use (proportionally). After 17+ years, I want to shut it
> down. However, in the last week it has gotten over 26,000 search requests
> from over 1400 unique IP addresses. I guess this is very small compared
> to the number of people who try to find relevant functions. The trouble is
> that, when I look at what people search for, I doubt that they will find
> what they want - they get either much to much or not what they are looking
> for.

Nothing actionable here, but yep! A tough situation.

> And sometimes I wonder who manages the task views. I think they are often
> outdated, but it must be an enormous job to keep them up to date, so that
> is understandable. The article points this out but might say a little
> more. Perhaps it would not be too much to send email to all package
> maintainers asking them if their packages should be included in some task
> views that now do not include them, and also include this suggestion (not
> requirement) in the email that goes to owners of new packages.

I added another sentence to flesh out the substance of the task view discussion.

> I do not understand the point at the top of p. 4 about keeping packages off
> CRAN. There are far too many packages already, and the kind of requirements
> that CRAN has now seem reasonable to me. (I say this even though I had
> great trouble with the one package I maintained, acepack*, for several
> years, because much of it was written in Fortran and I kept being asked to
> correct Fortran errors as a result of changes in the compiler. Finally
> someone took it over who knows Fortran. The point is that these requests
> were perfectly reasonable ones.)

Thanks for the note; I clarified.

> What is a "linter"?

Great point; I added a brief explanation.

> I think that the paper should say something about specialized R-sig lists
> and other mailing lists. The basic R-help list seems to have gotten to the
> point where trying to keep up with it is not useful. But I find
> r-sig-mixed-models to be quite useful in learning about new packages and
> capabilities, and not all that overwhelming. (Of course I look at the
> subject lines and maybe open 10% of the posts, and read 10% of those.)
> There is also a list for r-announce, that I thought had the function of
> announcing new packages, but it seems to be dead.

A good option to include. I added this when discussing "other" options for finding guidance.

## Reviewer 2


> The most important feature of a good search tool is the ranking of
> the results, which is completely omitted from this paper. A search
> engine without ranking is not very useful.

A good thing to address, and I added this to a new sentence in the last paragraph of the "Search" section.

> When surveying the package search tools, the search terms the
> authors used do not represent the terms (new) R users would use. (See
> the linked Wikiversity page.) For example, if somebody  searches for
> "readLines", the person already knows the function to read in lines of
> files, and a simple `?readLines` command in R takes her to relevant
> manual page. A more plausible search phrase is "read lines from
> files", etc. Similarly, the other search terms the authors used are
> also poor in my opinion. I suggest the authors use better search
> terms, together with "known" correct results, to evaluate the search
> tools. For example "visualization" (and also "visualisation"!) should
> find ggplot2, "permutation test" should find coin (see
> https://rviews.rstudio.com/2018/10/22/searching-for-r-packages/),
> "networks" should find igraph, "web" should find shiny, json should
> find "jsonlite", etc. It should be also possible to ask the developers
> of some of the search tools for real search terms users use.

I agree in substance, absolutely, and this is part of why we did not include any of these search results in the paper itself. Spencer Graves, the author of the Wikiversity page where these queries are laid out, would welcome edits from interested community members to make them more realistic. This is not part of the content of the paper, and I would not care to make edits in that Wikiversity page as part of the paper acceptance process.

> The figure is not particularly informative, is there a more
> interesting feature in the data that is worth showing?

I agree that it's not the most thrilling figure ever created. The survey was very simple; we asked just one question, with no demographic or geographic information. There isn't another figure we could create, since we only asked the one question. I don't have particularly strong feelings about including or exluding this figure and I leave it to the editor's discretion about which would be a better option.

> The paper might get out-of-date quickly, if new tools are
> introduced. Is there anything we can do to avoid this? For example,
> could the authors try to improve the
> https://www.r-project.org/search.html web page, to include new tools?

This is a great point; this is a paper that is addressing a community at a certain point in time. I would love to work with the R core team to update the Search options, and I added a sentence suggesting that changes could be due there. Especially since Jonathan Baron wants to stop supporting his search site!

> Could the packagesurvey R package be published on CRAN?> 

Certainly it technically could, and all the authors have experience publishing packages on CRAN. I don't see a strong reason to do so, as the benefit of this data set for pedagogical or other broad use is not large. I published the survey results as a package for transparency and for package authors who are interested; I believe publishing on GitHub meets those goals.
