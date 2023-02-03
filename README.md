# maps-heat-IR

Visualises how 35°C+ days will change in Australia in the coming decades.

## Use + Remix rights

![[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0)](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)

These charts, as well as the analyses that underpin them, are available under a Creative Commons Attribution 4.0 licence. This includes commercial reuse and derivates.

<!-- Do any of the data sources fall under a different licence? If so, describe the licence and which parts of the data fall under it here! if most of it does, change the above and replace LICENCE.md too -->

Data in these charts comes from:

* [NARCliM1.5: NSW DPIE](https://climatedata-beta.environment.nsw.gov.au/)

**Please attribute 360info and the data sources when you use and remix these visualisations.**

## Reproduce the analysis

> **Note:** this repo just contains the interactive map and processed data. If you're looking to reproduce the processed data from the original DPIE collections, you can find the analysis in [360-info/climate-projections-narclim15](https://github.com/360-info/climate-projections-narclim15)

### 💨 Quickstart: use the dev container

This project comes with a ready-to-use [dev container](https://code.visualstudio.com/docs/remote/containers) that includes everything you need to reproduce the analysis (or do a similar one of your own!), including [R](https://r-project.org) and [Quarto](https://quarto.org).

1. [Launch this project in GitHub Codespaces](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=[report_codespaces_id])
2. If you have Docker installed, you can build and run the container locally:
  - Download or clone the project
  - Open it in [Visual Studio Code](https://code.visualstudio.com)
  - Run the **Remote-Containers: Reopen in Container** command

Once the container has launched (it might take a few minutes to set up the first time), you can run the analysis scripts with:

```sh
quarto render
```

Or look for the `.qmd` files to modify the analysis.

### Manual setup

To setup a development environment manually, 

You'll need to:
- [Download and install Quarto](https://quarto.org/docs/get-started)
- [Download the install R](https://www.r-project.org)

Now, render the `.qmd` files to the `/out` directory with:

```sh
quarto render
```

## Help

If you find any problems with our analysis or charts, please feel free to [create an issue](https://github.com/360-info/maps-heat-ir/issues/new)!
