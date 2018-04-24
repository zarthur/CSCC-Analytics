# Getting Started - Anaconda

The preferred method of executing the notebooks is with
[Anaconda](https://www.anaconda.com/download).

## Using Anaconda

Download notebook zip file and extract its contents.

Download [Anaconda](https://www.anaconda.com/download) and follow the
[installation instructions](https://docs.anaconda.com/anaconda/install/) to
install the software.

After installation is complete, the run the *Jupyter Notebook* program from
the Start Menu, browse to the location to which the notebooks were extracted,
and open the desired notebook.

Near the beginning of most notebooks, one cell contains code necessary to
install third-party libraries using `pip`.  Because some of these libraries
require non-Python code to be compiled, this step can fail in Windows. An 
alternative method of installing the libraries using the Anaconda Prompt and
`conda` is provided.

To install all the required libraries for all the notebooks at once, open the 
Anaconda prompt and execute the following command.

``` shell
conda install -c conda-forge --yes pandas lxml requests xlrd geopandas seaborn statsmodels beautifulsoup4 textblob tinydb folium python-docx  plotly boto3
```

After executing the `conda install` command, execute the following in Anaconda
prompt.

``` shell
pip install requests_oauthlib squarify dash dash-renderer dash-html-components dash-core-components
```

These installation commands have been verified on Windows 10 64-bit and may not
work with other versions of Windows.

