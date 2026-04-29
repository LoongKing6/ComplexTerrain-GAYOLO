# ComplexTerrain-GAYOLO

我们只公布部分代码，等论文收录再公布全部代码。We are releasing only a portion of the code for now; the full code will be made available once the paper is accepted.

# paper:A Graph Convolutional Aggregation and Attention Capture Network for Edge-aware Power Line Segmentation with Complex Terrain.

If you want to refer to the paper’s model alongside the code: the model section is located in `PowerLine-MTYOLOv11` within the `v8` directory under `models`, and the `block` is in the `modules` directory. 

Link to the MPCD dataset:https://github.com/phd-benel/PowerLine-MTYOLO


## How to Run

### Clone this Repository

```shell
git clone https://github.com/Tairan4356/ComplexTerrain-GAYOLO.git
cd ComplexTerrain-GAYOLO
```

### Install Requirements

```shell
# Python version 3.12
pip install -r requirements.txt
```

### Model Path

```shell
ultralytics/models/v8/PowerLine-MTYOLOv11.yaml
```

### train

```shell
python train.py
```

### validate

```shell
python val.py
```

