Meshgraphnet_pytorch
PyTorch implementation of MeshGraphNet (GNN) with three benchmark studies:

Deformed flag
CFD
Deformed plate

<p align="center">
  <img src="https://github.com/user-attachments/assets/948533fd-55a2-425c-8fa9-7778f72e3970" width="20%" alt="Deformed flag simulation" loop="infinite" autoplay>
  <img src="https://github.com/user-attachments/assets/e8749c06-160b-4e9c-a972-521fce4d11e0" width="50%" alt="CFD" loop="infinite" autoplay>
  <img src="https://github.com/user-attachments/assets/bc1544c3-7798-4d7f-920c-dac451d1e683" width="20%" alt="Deformed plate" loop="infinite" autoplay>
</p>

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
