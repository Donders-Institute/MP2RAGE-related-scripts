# MP2RAGE scripts

- T1 maps estimation using the MP2RAGE sequence
- T1 map correction using an additional B1 map
- Background noise removal by using a "robust"/regularized version of the combination of the two inversion time images

These functions can be called with BIDS-wrappers (the functions named `bids_*`) to automatically process BIDS data repositories

## Installation

In the Environment tab of the Matlab window, click on `Add-ons` > `Get Add-ons` and search for "MP2RAGE". In the Add-On Explorer, navigate to the toolbox and click on `Add` and follow the instructions. For `here <https://nl.mathworks.com/help/matlab/matlab_env/get-add-ons.html>`__ more information.

Alternatively, you can `download <https://github.com/Donders-Institute/MP2RAGE-related-scripts/releases>`__ the MP2RAGE toolbox file yourzelf, and double click the `MP2RAGE.mltbx` file from within the Matlab File/Folder panel.
