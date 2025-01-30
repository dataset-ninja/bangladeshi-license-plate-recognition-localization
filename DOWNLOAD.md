Dataset **Bangladeshi License Plate Recognition: License Plate Localization** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4NDVfQmFuZ2xhZGVzaGkgTGljZW5zZSBQbGF0ZSBSZWNvZ25pdGlvbjogTGljZW5zZSBQbGF0ZSBMb2NhbGl6YXRpb24vYmFuZ2xhZGVzaGktbGljZW5zZS1wbGF0ZS1yZWNvZ25pdGlvbjotbGljZW5zZS1wbGF0ZS1sb2NhbGl6YXRpb24tRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiTmlFK09FTTVjR3BFNUg5VFp6QzIrZWNjeVVBL1g0WjJKUEI2Uk1nQ1c2ND0ifQ==)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Bangladeshi License Plate Recognition: License Plate Localization', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/syednahinhossain/bangladeshi-license-plate-recognition-dataset/).