This is the repository for *Conflict and Cultural Heritage: A Moral Analysis of the Challenges of Heritage Protection*, by Helen Frowe and Derek Matravers. This is the third paper in the J. Paul Getty Trust Occasional Papers in Cultural Heritage Policy series and was first published October 15, 2019, by Getty Publications. It is available online at [http://www.getty.edu/publications/occasional-papers-3/](http://www.getty.edu/publications/occasional-papers-3/) and may be downloaded free of charge in multiple formats.

## About the Book

In 2016, in response to recent attacks on cultural heritage sites in Syria, Iraq, and Timbuktu, the J. Paul Getty Trust convened a meeting at the British Academy in London to discuss the need for an international framework to protect cultural heritage in zones of armed conflict. To further explore these questions, the Trust subsequently launched the series J. Paul Getty Trust Occasional Papers in Cultural Heritage Policy.
 
In this third issue of the series, philosophers Helen Frowe and Derek Matravers pose a key question: what is the appropriate response to attacks on cultural heritage? They assert that we must more carefully consider the morality of using deadly military force to protect cultural heritage. Frowe and Matravers question the leading argument that there is a causal relationship between the destruction of cultural heritage and genocide, and they further argue that the defense of heritage must not be treated with the same weight or urgency—and thus should not be protected according to the same international policies—as the defense of human lives. By calling for expanded theory, empirical data, and the consideration of morality in the crafting of international resolutions, Frowe and Matravers present a compelling, thoughtful critique that stimulates debate on this critical topic.
 
## Using this Repository

This is one in series of multiformat publications using [Quire](http://www.getty.edu/publications/digital/platforms-tools.html), Getty’s new publishing framework. Quire is currently in private beta, with the goal of it being released as free and open source software in the future. In the meantime, users are encouraged to request access at http://bit.ly/quire-beta. This repository can also be run locally to build the online site (but not the PDF or ebook formats) with [Hugo](https://gohugo.io/), the [static site generator](https://www.smashingmagazine.com/2015/11/modern-static-website-generators-next-big-thing/) at the core of Quire. 

We are dedicated to maintaining this publication for years to come at the permanent URL, [http://www.getty.edu/publications/heritagemanagement/](http://www.getty.edu/publications/occasional-papers-3/), and in its various formats and incarnations. For any updates to the book, we will be following something between an app and traditional book publication model. Updates will only be made in regulated chunks as formal revisions and new editions and will always be thoroughly documented here in the repository, as well as in the revision history included with each of the book’s many formats.

The primary content pieces of the book can be found in the `data` and `content` directories. The master branch represents the current, published edition at all times, and the revisions branch, when present, will show changes currently under consideration. We invite you to submit suggestions or corrections via pull request on the revisions branch, by posting an issue, or by emailing us at [pubsinfo@getty.edu](mailto:pubsinfo@getty.edu).

## Development Notes

This project was last built with the following software versions:

- Quire 0.17.0
- Node 8.12.0 / npm 6.4.1
- Hugo 0.53
- PrinceXML 12.4
- Pandoc 2.3.1

While v0.17.0 of the core Quire Starter Theme was used, a number of customizations were made specifically to bring the design inline with previous papers in the series which we not originally published with Quire. Within the theme itself, changes were made to the `source/css/variables.scss` and `source/css/print.scss` files and two new open license fonts were included: Archivo Narrow and Source Sans Pro. Outside of the theme, in the project’s `layouts` directory, a number of custom templates are included, notably a custom cover layout, and some custom partial templates to allow for modest customization to other elements of the book. The `q-note` shortcode was also added to allow for endnotes in the book rather than the usual footnotes other Quire books use by default.

## License

© 2019 J. Paul Getty Trust

This text of this work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International Public License](https://creativecommons.org/licenses/by-nc/4.0/). The cover image is reproduced with the permission of the rights holder acknowledged in the caption and is expressly excluded from the CC BY-NC license covering the rest of this publication. The image may not be reproduced, copied, transmitted, or manipulated without consent from the owner, who reserves all rights.
