Dataset **Safety Helmet and Reflective Jacket** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4MjlfU2FmZXR5IEhlbG1ldCBhbmQgUmVmbGVjdGl2ZSBKYWNrZXQvc2FmZXR5LWhlbG1ldC1hbmQtcmVmbGVjdGl2ZS1qYWNrZXQtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiQi95ZG9UQVQrSnFHQTlndVExUUc4TmwzY1R6TzgvR0xZYXZQdzR2N0ZmZz0ifQ==)

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