## Dash Dataset View Tools
This tool supports exploratory data analysis based on CSV data.
### Components
- Data preview
- Correlation matrix

### How to use

```zsh
% conda env create -n [ENV_NAME] -f conda_env.yml
% python app.py
```

#### Data preview
using [Dash DataTable](https://dash.plotly.com/datatable)
![DataPreview.png](./DataPreview.png)

#### Correlation matrix
using [Plotly Annotated Heatmap](https://plotly.com/python/annotated-heatmap/)
this library make display data in cells and column names can be written on both axes.
![CorrelationMatrix.png](./CorrelationMatrix.png)