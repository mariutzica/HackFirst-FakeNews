Data registration files for HAND model.

NOTES

1. The original file (USGS-Streamgages-HUC10190005.tsv) not in directory because too large to upload to GitHub.
2. The iPython notebook contained here includes all of the data preprocessing/file reformatting, metadata declarations, and POST requests to register the data files to the MINT Data Catalog
3. Currently the configuration goes to sandbox. In order to be able to officially register the data, the following are needed:
    - Upload data to DataX and obtain URL (Maria does not have the right permissions to do this)
    - Obtain provenance id from Dan for the Data Catalog.
    - Take out the resource ids & change URL to the official MINT Data catalog URL.
