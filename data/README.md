# Data Folder

It is of utmost importance that you **do not** push any of this data to GitHub or any other public repository, as doing so could result in serious privacy violations and compromise sensitive information. The data should be stored in this folder locally only. 

Here are some essential guidelines:

- Save the raw data file you received from the client in this folder, adding a clear identifier like `data_raw` or `data_original` to distinguish it. 
- **NEVER** alter the original data file. Keeping this untouched original is vital, ensuring you always have a backup in case of unexpected issues. 
- You can then create scripts in the `src` folder to process the data, and if you decide to save the processed data, please use a different filename like `data_processed` within this `data` folder.
