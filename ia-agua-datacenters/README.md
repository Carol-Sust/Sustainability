# AI and water: European data centres in water-stressed basins

## Question
How many European data centres are located in basins with high or extremely high water stress, and how does that risk change by 2050?

## Short answer
_To be completed after the analysis._

## Data sources
- OpenStreetMap (Overpass API): data centre locations
- WRI Aqueduct 4.0: current and projected water stress
- ERA5-Land (Copernicus): daily maximum temperature

## How to reproduce
1. `conda env create -f environment.yml`
2. Run the notebooks in `notebooks/` in order (00 → 06)

## Scope and decisions
- Countries: EU-27 + United Kingdom, Norway, Switzerland
- Hot day threshold: 30 °C
- All parameters are in `config.yaml`

## Limitations
_To be completed._