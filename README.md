# Community mapping docs
Note: We are moving away from use of the term "stakeholder" due to its colonial origin. That term still appears in these documents, but will be replaced with alternative language when possible. 
# README

This is a dump of very untidy materials! It will likely be improved the next time this exercise is undertaken or in the development of a mapping tool.

Suggested order of use:
1. [Why we map](./why-map.md)
2. [How we map](./how-we-map.md)
3. [Sharepoint list settings](./how-we-map-sharepoint-lists.md)
4. [Code to convert sharepoint downloads to *xlsx* kumu structure](./sharepoint-to-kumu-xlsx.py)
5. [Kumu display settings - internal](./kumu-display-settings-internal) - this is a dump of the kumu syntax for display settings used in the Turing E&S *internal* map
6. [Kumu display settings - public](./kumu-display-settings-internal) - this is a dump of the kumu syntax for display settings used in the Turing E&S *public* map
7. [Image used for the Kumu presentation front cover](./kumu-public-cover.png)
8. [Kumu presentation slide text](./kumu-descriptions.md)


These files aren't used, but are kept for future reference!
1. [Conda environment for running the python](./kumu-env.yml) - I just used the TTW one in the end :)
2. [Code to convert sharepoint downloads to *json* kumu structure](./sharepoint-to-kumu-json.py) - played with this when i was struggling to upload the xlsx to kumu. Turns out it didn't like the ID variable which sharepoint creates (kumu creates its own) and it was causing a clash. This was resolved by deleting the sharepoint ID. This bug was fixed after chatting to folks on kumu slack and some exchanges with the developers :).
3. [pptx I used to develop the kumu cover images](./images-dev.pptx)
4. [Code to compare the list of slack users downloded to those I'd added with a "slack" interaction](./compare-list-slack-sharepoint.py) - This was used when I was making sure I'd added everyone with slack interaction

# CITATION
Please cite as 10.5281/zenodo.15320348

# LICENSE
- Code is released on an MIT license.
- Documentation is released on a CC-BY-4.0 license