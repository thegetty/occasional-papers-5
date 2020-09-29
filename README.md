This is the repository for “Cultural Heritage under Siege: Laying the Foundation for a Legal and Political Framework to Protect Cultural Heritage at Risk in Zones of Armed Conflict,” edited by James Cuno and Thomas G. Weiss. This is the fourth paper in the *J. Paul Getty Trust Occasional Papers in Cultural Heritage Policy* and was first published September 8, 2020, by Getty Publications. It is available online at [http://www.getty.edu/publications/occasional-papers-4/](http://www.getty.edu/publications/occasional-papers-4/) and may be downloaded free of charge in multiple formats.

## About the Book

In 2016, in response to recent attacks on cultural heritage sites in Syria, Iraq, and Timbuktu, the J. Paul Getty Trust convened a meeting at the British Academy in London to discuss the need for an international framework to protect cultural heritage in zones of armed conflict. To further explore these questions, the Trust subsequently launched the *J. Paul Getty Trust Occasional Papers in Cultural Heritage Policy*.

The fourth issue of the *J. Paul Getty Trust Occasional Papers in Cultural Heritage Policy* is the result of a multiday convening on the issue of cultural heritage under siege. It features an edited collection of presentations and discussions by nineteen scholars and practitioners of diverse specialties related to the field of cultural heritage.

## Using this Repository

This is one in series of multiformat publications using [Quire](http://www.getty.edu/publications/digital/platforms-tools.html), Getty’s new publishing framework. Quire is currently in private beta, with the goal of it being released as free and open source software in the future. In the meantime, users are encouraged to request access at http://bit.ly/quire-beta. This repository can also be run locally to build the online site (but not the PDF or ebook formats) with [Hugo](https://gohugo.io/), the [static site generator](https://www.smashingmagazine.com/2015/11/modern-static-website-generators-next-big-thing/) at the core of Quire.

We are dedicated to maintaining this publication for years to come at the permanent URL, [http://www.getty.edu/publications/occasional-papers-4/](http://www.getty.edu/publications/occasional-papers-4/), and in its various formats and incarnations. For any updates to the book, we will be following something between an app and traditional book publication model. Updates will only be made in regulated chunks as formal revisions and new editions and will always be thoroughly documented here in the repository, as well as in the revision history included with each of the book’s many formats.

The primary content pieces of the book can be found in the `data` and `content` directories. The master branch represents the current, published edition at all times, and the revisions branch, when present, will show changes currently under consideration. We invite you to submit suggestions or corrections via pull request on the revisions branch, by posting an issue, or by emailing us at [pubsinfo@getty.edu](mailto:pubsinfo@getty.edu).

## Development Notes

This project was last built with the following software versions:

- Quire 0.18.0
- Node 12.18.3 / npm 6.14.6
- Hugo 0.72
- PrinceXML 13.5
- Pandoc 2.10.1

While v0.18.0 of the core Quire Starter Theme was used, a number of customizations were made specifically to bring the design inline with previous papers in the series which we not originally published with Quire. Within the theme itself, changes were made to the `source/css/variables.scss` and `source/css/print.scss` files and two new open license fonts were included: Archivo Narrow and Source Sans Pro. Outside of the theme, in the project’s `layouts` directory, a number of custom templates are included, notably a custom cover layout, and some custom partial templates to allow for modest customization to other elements of the book. The `q-note` shortcode was also added to allow for endnotes in the book rather than the usual footnotes other Quire books use by default.

### Images Submodule

The cover images for the *Occasional Papers* are licensed from third parties for use exclusively in each publication. As such, they are kept in a separate, private repository, https://github.com/thegetty/occasional-papers-images/, which is linked to this main publication repository as a submodule in `static/img/cover/`. When cloning this repo for further development, you’ll permissions for the private repository and will need to clone recursively in order to clone both the main repo and the submodule.

```
git clone --recursive https://github.com/thegetty/occasional-papers-4.git
```

## License

© 2020 J. Paul Getty Trust

This text of this work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). The cover image is reproduced with the permission of the rights holder acknowledged in the caption and is expressly excluded from the CC BY-NC license covering the rest of this publication. The image may not be reproduced, copied, transmitted, or manipulated without consent from the owner, who reserves all rights.
