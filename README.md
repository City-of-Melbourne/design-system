# City of Melbourne Design System

First step towards creating an open source design system based on the DCI's internal design style guide.

See the live website at:

[https://city-of-melbourne.github.io/design-system/](https://city-of-melbourne.github.io/design-system/)

## Goal

Make the current design style guide (system) open source.


## Benefits

- Scale: Like scalable software but for design
- Open: Increase visibility both internally and externally
- Reuse: both internally and potentially externally
- Take lead in the digital design as council (win design system race against sydney)
- Join the leader: AU government is doing this already
- Kick start a project/prototype/mockup quickly


## Road map

- [x] Static version of the current style guide from a html dump of confluence
- [x] Generate site form markdown version of the documents
- [ ] Make components live 👈 doing
- [ ] Create a front-end framework based on the design system
- [ ] Create starter packs that allows people to get up and running quickly


## Tips for updating the website

- It takes 3-10 seconds for the code to generate and update from markdown to the HTML site, so you’ll need some patience to see changes!
- Make sure to keep the “layout” and “title” on every page.
- Reference the internal img folder only in order to retrieve image files. Don’t put the entire location in there. E.g. /img/image.png is correct, and /design-system/components/img/image.png will not work.
- Avoid tables at all costs. If you really, really have to, refer to use github’s markdown style for it, and you’ll probably have to get a dev to create a style for the website.
- Give a useful description to your commit, for version control.
