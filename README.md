# document_and_share
Strategies for documentation and sharing of data analyses.

## [Presentation](https://imperiallondon-my.sharepoint.com/:p:/g/personal/bms20_ic_ac_uk/EXGehX5v6jxNqpgeyd1LuNEBQKEXzFznBs4lmo6xbKrUXw?e=BjczKB) 

- ### How to share powerpoints 
1. `File -> Share -> Share...`
2. Share via OneDrive.
3. `File -> Share -> Copy link`
4. Navigate to the link and the click `Share` button in the upper right for more control over share settings. 

## Rmarkdown  

- ### [Template](https://neurogenomics.github.io/document_and_share/templates/rmarkdown_template.html)  

- ### [Example](https://neurogenomics.github.io/document_and_share/templates/rmarkdown_example.html) 

- ### [Plotly vignette](https://neurogenomics.github.io/document_and_share/vignettes/plotly.html) 

## Jupyter 

- ### [Template](https://neurogenomics.github.io/document_and_share/templates/jupyter_template.html)  

- ### [Example](https://neurogenomics.github.io/AD_CVD_genetics/code/DeGAs.html)   

    + [Animation example](https://neurogenomics.github.io/AD_CVD_genetics/code/DeGAs.html#2D-UMAP)

## Conda 

- [Here you can find a yaml file](https://github.com/neurogenomics/document_and_share/blob/main/templates/env.yml) that can be used to construct a conda env (named "`pyre`") that includes R, Python, and Jupyter, and all the necessary supporting packages. 

1. ### Create conda env  

```
conda env create -f https://github.com/neurogenomics/document_and_share/raw/main/templates/env.yml
```  

2. ### Add env to Jupyter 

``` 
python -m ipykernel install --user --name=pyre
```

3. ### Activate conda env  

```
conda activate pyre
```  

4. ### Start Jupyter  

``` 
jupyter notebook
```



