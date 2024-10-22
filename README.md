Meshgraphnet_pytorch
PyTorch implementation of MeshGraphNet (GNN) with three benchmark studies:

<table>
  <tr>
    <th>Deformed Flag</th>
    <th>CFD</th>
    <th>Deformed Plate</th>
  </tr>
  <tr>
    <td><img src="./world_anim.gif" width="150"/></td>
    <td><img src="./cfd.gif" width="400"/></td>
    <td><img src="./deform_plate.gif" width="150"/></td>
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

# Hyperparameter tune 
Timestep > hidden dimension == Layer > epoch > batch




References

1. https://github.com/google-deepmind/deepmind-research
2. https://medium.com/stanford-cs224w/learning-mesh-based-flow-simulations-on-graph-networks-44983679cf2d
3. https://github.com/wwMark/meshgraphnets


