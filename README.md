# Hungary population density project

This small project uses web scraping and pydeck to visualize the population density of Hungary

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.

```bash
pip install -r requirements.txt
```

## Usage

For quicker usage after installing the requirements you can run the imports and then countinue from this snippet

```python
df = pd.read_csv('Cities.csv')
df = df[['Name','Latitude','Longitude','PopulationEstimate2019-01-01']]
df.columns = ['Name','Latitude','Longitude','PopulationEstimate2019-01-01']
```