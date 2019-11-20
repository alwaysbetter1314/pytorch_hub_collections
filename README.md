## Introduction
collections for pytorch hub : models with weights
## TODO:
Except for models in [torch.hub,torchvison], Efficient-net should be added into this repo.


## Usage
1. you can check out the list of models:  
`torch.hub.list('chenfengshf/torch_hub_collections')`
2. load model and weights :  
`net = torch.hub.load('chenfengshf/torch_hub_collections','resnet18')`
> perhaps,the net is same as torchvison.models.resnet18(pretrained=True)

## Other
replace 'chenfengshf/torch_hub_collections' with follow items.
And other models gathered are as follows:
1. facebookresearch/WSL-Images

> ['resnext101_32x16d_wsl', 'resnext101_32x32d_wsl', 'resnext101_32x48d_wsl', 'resnext101_32x8d_wsl']

2. facebookresearch/FixRes

> 'fixresnet_50', 'fixresnet_50_CutMix', 'fixresnext101_32x48d'

3. pytorch/vision
> same as torchvison.models
