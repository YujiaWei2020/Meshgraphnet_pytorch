Meshgraphnet_pytorch
PyTorch implementation of MeshGraphNet (GNN) with three benchmark studies:

Deformed flag


<table>
  <tr>
    <td><img src="./world_anim.gif" width="250"/></td>
    <td><img src="./cfd.gif" width="250"/></td>
    <td><img src="./deform_plate.gif" width="250"/></td>
  </tr>
</table>

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
