---
# Display name
title: BGCFlow

#Use 1 for PI, 100 for Current Postdocs, 200 for current phds, 300 for current masters, 400 for current undergrads, 800 for alum postdocs, 810 for alum phds, 820 for alum masters, and 830 for alum undergrads, 900 for tools, 1000 for projects, 900 for tools, 1000 for projects
weight: 900

# Username (this should match the folder name)
authors:
- BGCFlow

#Author Names (alternative spellings etc)
names:
- BGCFlow

#Link to this when clicking on tool icons
toolurl: https://github.com/NBChub/bgcflow

# Is this the primary user of the site?
superuser: false

projects:
- Snakemake workflow for the analysis of biosynthetic gene clusters across large collections of genomes (pangenomes).

# Short bio (displayed in user profile at end of posts)
# bio: My research interests include distributed robotics, mobile computing and programmable matter.

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: github
  icon_pack: fab
  link: https://github.com/NBChub/bgcflow



# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
- Tools
- BGCFlow Tool

#any user groups to display on the page
display_groups:
- BGCFlow

research_area: true

research_area_tags:
- BGCFlow
- BGCFlow tool
---

BGCFlow is a systematic workflow for the analysis of biosynthetic gene clusters across large collections of genomes (pangenomes) from internal & public datasets. BGCFlow incorporates several genome analytics and mining tools  grouped into five common stages of analysis such as: (i) data  selection, (ii) functional annotation, (iii) phylogenetic  analysis, (iv) genome mining, and (v) comparative analysis.  Furthermore, BGCFlow provides easy configuration of different  projects, parallel distribution, scheduled job monitoring, an  interactive database to visualize tables, exploratory Jupyter  Notebooks, and customized reports.

![dag](https://github.com/NBChub/bgcflow/raw/main/workflow/report/images/rulegraph_annotated.png)

## Publication
> Matin Nuhamunada, Omkar S Mohite, Patrick V Phaneuf, Bernhard O Palsson, Tilmann Weber, BGCFlow: systematic pangenome workflow for the analysis of biosynthetic gene clusters across large genomic datasets, Nucleic Acids Research, 2024;, gkae314, [https://doi.org/10.1093/nar/gkae314](https://doi.org/10.1093/nar/gkae314)