# dl-miniproject

Creating dataset

- `create_dataset.ipynb` - Create new dataset from Instagram posts
- `download_dataset.ipynb` - Download images from predefined urls list
- `perturb_dataset.ipynb` - Define random perturbations and apply them to dataset

Downloading *.npz files:

``` bash
wget https://storage.googleapis.com/vit_models/imagenet21k+imagenet2012/ViT-B_16.npz

wget https://storage.googleapis.com/bit_models/BiT-M-R50x2-ILSVRC2012.npz
```

*.npz files should be placed in main project catalog.

Downloading imagenet labels:
```bash
wget https://storage.googleapis.com/bit_models/ilsvrc2012_wordnet_lemmas.txt
```

### Model details:

* [BiT - Google Repo](https://github.com/google-research/big_transfer)
* [ViT - Google Repo](https://github.com/google-research/vision_transformer)
* [ViT implementation](https://github.com/jeonsworld/ViT-pytorch)
* [ViT models](https://console.cloud.google.com/storage/browser/vit_models)
