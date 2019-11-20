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
