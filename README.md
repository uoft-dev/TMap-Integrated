# TMap Integrated
Updated version of the TMap, which can be found [here](https://github.com/uoft-dev/TMap).

## Integrated

* Firebase cloud functions for backend, to fetch and serve dataset updates.
  * ```fetch_dataset```: ```returns``` the most recent dataset.
  * ```update_dataset```: updates the dataset from github, from the backend.

* React native for front end, which queries the firebase cloud functions periodically to update dataset.
