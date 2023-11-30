Dataset **Safety Helmet and Reflective Jacket** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://www.dropbox.com/scl/fi/k6fwmfvvjj7fpgrbuu4ot/safety-helmet-and-reflective-jacket-DatasetNinja.tar?rlkey=ltr29rrqp6yarmil1gmyiu8my&dl=1)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Safety Helmet and Reflective Jacket', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/niravnaik/safety-helmet-and-reflective-jacket).