# MNIST-M

The MNIST dataset is really popular. But MNIST-M offers more in terms of data.
It's a extended version of MNIST dataset. All the images in this dataset have 
3 channels( RGB ) .

`mnistm.py` has all the necessary things to download the data.
All we needed to do is to import the `MNISTM` class from that script to the
main script `resnet_mnistM.py`. It works pretty much like `torchvision.dataset` .
