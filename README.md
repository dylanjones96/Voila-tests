# Using Voilà to render interactive slider plots

This repository was copied from https://github.com/binder-examples/voila. The test_number_.ipynb scripts were edited using the index.ipynb as a template. 


## This button will build a conda environment and launch jupyter-lab
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dylanjones96/Voila-tests/HEAD)

## This button will render the test8.ipynb notebook's outputs in a browser window using Voilà
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dylanjones96/Voila-tests/main?urlpath=voila%2Frender%2Findex_test8.ipynb)

## Some instructions lifted from host repository README

If you would like to use the same configuration as this repository but for another project, check out the following steps:

1. Make sure the repository is publicly available (on GitHub, Gitlab or as a [GitHub Gist](https://gist.github.com)
2. Define the dependencies in [`environment.yml`](./environment.yml). `requirements.txt` is also supported. In the dependency file, add `voila`.
3. Go to [mybinder.org](https://mybinder.org) and enter the URL of the repository.
4. In `Path to a notebook file`, select `URL` and use the Voilà endpoint: `voila/render/path/to/notebook.ipynb`
5. Click `Launch`.
6. Binder will trigger a new build if this is the first launch (or if there have been new changes since
   the last build). This might take a few minutes to complete. If an image is already available,
   the server will be able to start within a few seconds.

Here is an overview of the Binder configuration on [mybinder.org](https://mybinder.org):

![image](https://user-images.githubusercontent.com/591645/132292481-01f877c3-77f8-46ba-b265-23bd3e25f513.png)

For more details, check out the Voilà documentation on https://voila.readthedocs.io/en/latest/deploy.html#deployment-on-binder
