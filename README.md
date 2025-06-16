[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15320348.svg)](https://doi.org/10.5281/zenodo.15320348)

<mark>*** All material in this repository is shared as a work in progress. Some material may be missing, under review, or no longer in scope. Please  contact cassandra.gouldvanpraag@rcmcooperative.com if you have questions about reuse or contribution. *** </mark>

# Community mapping docs

Note: We are moving away from use of the term "stakeholder" due to its colonial origin. That term still appears in these documents, but will be replaced with alternative language when possible. 
# README

These materials were developed alongside the [Alan Turing Instute Environment and Sustianabilty Grand Challenge Stakeholer Map](https://cassgvp.kumu.io/alan-turing-institute-environment-and-sustainability). This map may no longer be updated or maintained. 

This is a dump of very untidy materials! It will likely be improved the next time this exercise is undertaken or in the development of a mapping tool.

Suggested order of use:
1. [Why we map](./docs/why-map.md)
2. [How we map](./docs/how-we-map.md)
3. [Data flow overview](./docs/stakeholder-map-process-workflow.pdf) - this shows how data is integrated over different sources. Ticks show the bits which are operational! (There is still lots of work to do!)
4. [Sharepoint list settings](./docs/how-we-map-sharepoint-lists.md)
5. [Code to convert sharepoint downloads to *xlsx* kumu structure](./code/sharepoint-to-kumu-xlsx.py)
6. [Kumu display settings - internal](./kumu-settings/kumu-display-settings-internal) - this is a dump of the kumu syntax for display settings used in the Turing E&S *internal* map
7. [Kumu display settings - public](./kumu/settings/kumu-display-settings-internal) - this is a dump of the kumu syntax for display settings used in the Turing E&S *public* map
8. [Image used for the Kumu presentation front cover](./kumu-settings/kumu-public-cover.png)
9. [Kumu presentation slide text](./kumu-settings/kumu-descriptions.md)


These files aren't used, but are kept for future reference!
1. [Conda environment for running the python](./DO-NOT-USE/kumu-env.yml) - I just used the TTW one in the end :)
2. [Code to convert sharepoint downloads to *json* kumu structure](./DO-NOT-USE/sharepoint-to-kumu-json.py) - played with this when i was struggling to upload the xlsx to kumu. Turns out it didn't like the ID variable which sharepoint creates (kumu creates its own) and it was causing a clash. This was resolved by deleting the sharepoint ID. This bug was fixed after chatting to folks on kumu slack and some exchanges with the developers :).
3. [pptx I used to develop the kumu cover images](./DO-NOT-USE/images-dev.pptx)
4. [Code to compare the list of slack users downloded to those I'd added with a "slack" interaction](./DO-NOT-USE/compare-list-slack-sharepoint.py) - This was used when I was making sure I'd added everyone with slack interaction

# CITATION
Gould van Praag, C. (2025). RCM Cooperative Community Mapping Workflow. Zenodo. https://doi.org/10.5281/zenodo.15320348

# LICENSE
- Code is released on an MIT license.
- Documentation is released on a CC-BY-4.0 license