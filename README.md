# Sato Lab
Projects to analyse data produced by the Sato Lab.

## [Comparative pathogenicity of SARS-CoV-2 Omicron subvariants including BA.1, BA.2, and BA.5](https://doi.org/10.1038/s42003-023-05081-w)

My analysis on the data produced for this paper integrates the data behind Figures 1A and 1B.

![Figures 1A and 1B](https://github.com/Mike-Honey/Sato-Lab/raw/main/doi.org%2010.1038%20s42003-023-05081-w%20Comparative%20pathogenicity%20of%20SARS-CoV-2%20Omicron%20subvariants%20including%20BA.1%2C%20BA.2%2C%20and%20BA.5/doi.org-10.1038%20s42003-023-05081-w-Figure-1-A-and-B.png)

The tool used is [Power BI](https://powerbi.microsoft.com/). This is an interactive data visualisation tool, that allows interactive filtering and exploration of the data.  I have used this to first reproduce similar charts to those shown in the paper, and then explored a series of alternative presentations of the same data.

### Reproduction

This page follows the style of the original figures. Being interactive, the user can filter the list of subvariants (Inoculum), or cross-filter by selecting a column in the charts. The tables below present the detailed data.

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=32037d60b8a6d4117483)

[![Click to view and interact with the report](https://github.com/Mike-Honey/Sato-Lab/raw/main/doi.org%2010.1038%20s42003-023-05081-w%20Comparative%20pathogenicity%20of%20SARS-CoV-2%20Omicron%20subvariants%20including%20BA.1%2C%20BA.2%2C%20and%20BA.5/repro.png)](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=32037d60b8a6d4117483)

### Column Charts, Power BI Theme

This page presents the same charts as the Repro page, but the theme applied is a Power BI built-in blue gradient: "Storm". From a dataviz perspective, I think this does a better job of suggesting the progressive evolution of the virus. The strong contrasting colors in the original figure area a bit distracting, and I would normally not use Black, Grey or Red for a series in a visualisation.

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=56b4855092b70698555d)

[![Click to view and interact with the report](https://github.com/Mike-Honey/Sato-Lab/raw/main/doi.org%2010.1038%20s42003-023-05081-w%20Comparative%20pathogenicity%20of%20SARS-CoV-2%20Omicron%20subvariants%20including%20BA.1%2C%20BA.2%2C%20and%20BA.5/column-charts.png)](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=56b4855092b70698555d)


### Line Charts

This page swaps the column charts for Line Charts. These allow a dynamic Y-axis minimum and a continuous X-axis. This can make the relative changes and growth more obvious among the variants, and are a more accurate representation of the Hours measured.  I chose slightly darker gradients from the "Storm" palette for the Inoculum series, to separate them visually.

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=6a66623c37b940635209)

[![Click to view and interact with the report](https://github.com/Mike-Honey/Sato-Lab/raw/main/doi.org%2010.1038%20s42003-023-05081-w%20Comparative%20pathogenicity%20of%20SARS-CoV-2%20Omicron%20subvariants%20including%20BA.1%2C%20BA.2%2C%20and%20BA.5/line-charts.png)](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=6a66623c37b940635209)


### Race Charts

This page presents animated race charts to contrast the relative progressions. I included inferred data for the 12, 36 and 60 hour observations, to align the timing of the 3 race charts.  While of course these are less accurate to view, they do give a feel for the progression of each infection metric over the 72-hour period that was measured.

[Link to interactive DataViz](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=06c4732f54588ca041cb)

[![Click to view and interact with the report](https://github.com/Mike-Honey/Sato-Lab/raw/main/doi.org%2010.1038%20s42003-023-05081-w%20Comparative%20pathogenicity%20of%20SARS-CoV-2%20Omicron%20subvariants%20including%20BA.1%2C%20BA.2%2C%20and%20BA.5/race-charts.png)](https://app.powerbi.com/view?r=eyJrIjoiYmI2Njc0YmQtYjgwNS00YWExLWIxNjItM2MyZGQ0NmFmYmE0IiwidCI6ImRjMWYwNGY1LWMxZTUtNDQyOS1hODEyLTU3OTNiZTQ1YmY5ZCIsImMiOjEwfQ%3D%3D&pageName=06c4732f54588ca041cb)

[Link to watch the video](https://youtu.be/wKzirRltcGI)

## 🤝 Support

Contributions, issues, feature requests and sponsorship are all welcome!

Give a ⭐️ if you like this project!
