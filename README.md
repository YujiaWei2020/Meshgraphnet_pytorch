Meshgraphnet_pytorch
PyTorch implementation of MeshGraphNet (GNN) with three benchmark studies:

Deformed flag
<a href="url"><img src="[http://url.to/image.png](https://github.com/YujiaWei2020/Meshgraphnet_pytorch/blob/main/world_anim.gif)" align="left" height="48" width="48" ></a>

# Dataset Download 
Navigate to the dataset directory
```
cd path/to/dataset/directory
```
Run the following command to generate the .idx file:
```
python -m tfrecord.tools.tfrecord2idx <file>.tfrecord <file>.idx
```

# Excute
```
python deformedflag.py
python cfd.py
python deformedplate.py
```



References

1. https://github.com/google-deepmind/deepmind-research
2. https://medium.com/stanford-cs224w/learning-mesh-based-flow-simulations-on-graph-networks-44983679cf2d
3. https://github.com/wwMark/meshgraphnets
