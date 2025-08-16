# The Economist Data Team's Grid/Tile Choropleth Map

Recreating The Economist's Grid Choropleth Map in {ggplot2}

## Motivation

I am a huge fan of The Economist's [data team](https://www.economist.com/topics/graphic-detail). Their iconic design and elegant approaches to data visualization are extremely flexible, easily translating between print columns, online, and social (especially [Instagram](https://www.instagram.com/theeconomist/)). One of my favorite visualizations is The Economist data team's effective grid tile choropleth map for the 50 states and DC.

### Example

This comes from the June 26, 2025, issue covering the impacts of the (then yet-to-be-enacted) OBB: [Why America’s hospitals don’t want their taxes cut](https://www.economist.com/united-states/2025/06/26/why-americas-hospitals-dont-want-their-taxes-cut).

![viz]()

© 2025 The Economist.

### 1. Data

Data for the article comes from the [The Hilltop Institute's](https://hilltopinstitute.org/) report [What’s the Impact of Eliminating Medicaid Provider Taxes?](https://hilltopinstitute.org/wp-content/uploads/publications/EliminatingProviderTaxes_6May2025.pdf?highlight=Eliminating%20Provider%20Taxes%20May%206%202025) published on May 26, 2025, and available at <https://hilltopinstitute.org/wp-content/uploads/publications/EliminatingProviderTaxes_6May2025.pdf?highlight=Eliminating%20provider>.

### 2. Recreating the Visualization in {ggplot2}

### 3. Finessing Final Size

### 4. Creating a `econ_choropleth()` Function