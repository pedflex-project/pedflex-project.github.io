---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: ''
---

## Accompanying material for the PEDFLEX project proposal.

### Letters of intention

{% for letter in site.data.letters %}

- **{{ letter.acronym }}** [{{letter.filename}}]({{letter.filename | append: '.pdf' | prepend: '/assets/letters/' | prepend: site.baseurl}})
  ![{{letter.filename}}]({{letter.filename | append: '.svg' | prepend: '/assets/letters/' | prepend: site.baseurl}})


{% endfor %}

[Back to top](#)
