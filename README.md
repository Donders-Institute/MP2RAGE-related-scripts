# MP2RAGE scripts

- T1 maps estimation using the MP2RAGE sequence
- T1 map correction using an additional B1 map
- Background noise removal by using a "robust"/regularized version of the combination of the two inversion time images

These functions can be called with BIDS-wrappers (the functions named `bids_*`) to automatically process BIDS data repositories

## Installation

In the Environment tab of the Matlab window, click on `Add-ons` > `Get Add-ons` and search for "MP2RAGE". In the Add-On Explorer, click on `Add` and follow the instructions. Alternatively, you can download (and unzip) the data yourself, and add the path or double click the `MP2RAGE.mltbx` file in the Matlab File/Folder panel