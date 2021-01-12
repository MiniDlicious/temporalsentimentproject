# Temporal Sentiment Analysis and Visualization

A Text Mining project containing data extraction, model selection, model validation and visualization. Project is described in the [report](report/report.pdf) and the code is for now in notebooks. There is one notebook for fetching game reviews from Steam API, [steam reviews.ipynb](notebooks/steam%20reviews.ipynb), and another one for the analysis [tempsent.ipynb](notebooks/tempsent.ipynb).

The template for the report is taken from [LiU Thesis Template](https://gitlab.ida.liu.se/olale55/liuthesis).

![Visualization demo](/plots/demo.png)

Goal is to generalize and transform this functionality into a standalone package [tempsent](https://github.com/MiniDlicious/tempsent).

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages required to run the notebooks.


## Usage

The notebooks contain documentation and comments for most parts, but it is advised to not just run the complete notebook. Data is not included due to Terms of Use, however it can be fetched using the [steam reviews.ipynb](notebooks/steam%20reviews.ipynb) notebook. 

Note that some model can be computational heavy.

## Contributing

Contributing to this project is done in the package repository [tempsent](https://github.com/MiniDlicious/tempsent).

## Acknowledgements

- [Ola Leifler](https://gitlab.ida.liu.se/olale55/liuthesis) 
- [Jeremy Miller](https://gist.github.com/jeremymiller00/81f1116bc12bb71fc6227e49c4c6796c) 
- [Steam](https://store.steampowered.com/) 

## License

[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)