# RCS Genomics Visualization
Tutorials on how to create typical plots with genomics data

## Conda environment

for Python: 

```
conda create --name genomics -c conda-forge python=3.10 pandas matplotlib jupyter seaborn
```

for R:

```
conda create --name r4-genomics -c conda-forge r-base=4.1.3 jupyter r-irkernel r-ggplot2 r-markdown r-tidyr
```

## Downloading data

I did not include the data here because it is already hosted online elsewhere.  I included a cell in the Python notebook to download the data.  Alternatively, you can do it manually following:

1. Create directories here for ```data/heatmap``` and ```data/circos```
2. In ```data/heatmap``` download the files from [here](https://zenodo.org/record/2529926#.YwaRPfHMIas).
3. In ```data/circos``` download the files from [here](https://zenodo.org/record/4494146#.YwaTwPHMIas).
