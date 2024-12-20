# Cognitive-Intelligence-UET
This is a repo for the Cognitive Intelligence course @ VNU-UET

# How to run
1. create a virtual environment
```
    conda create -n iic python=3.10
    conda activate iic
```

2. install the requirements
```
    pip install -r requirements.txt
```

3. run the notebook
We provided 2 notebooks, in `working` director, `_train_v1.ipynb` and `xafe-visualizer.ipynb`. You can run them to train the model.

`_train_v1.ipynb` is the main notebook to train the model. It will save the checkpoints to `working/protopnet_v3` directory.
`xafe-visualizer.ipynb` is the notebook to visualize the data and infer from the model. It will load the model from `working/protopnet_v3` directory.

If you want to train the model, first get the dataset from kaggle (`CUB_200_2011`), then put it in `input` directory. The structure should be like this:
```
working
└── cub2002011
    ├── CUB_200_2011
    ├── cvpr2016_cub
    └── segmentations
```

# Overview of the repo
```
.
├── input
│   └── cub2002011
├── requirements.txt
└── working
    ├── protopnet_v1
    ├── protopnet_v3
    ├── _train_v1.ipynb
    └── xafe-visualizer.ipynb
```

# Team members
- 22028108 - Nguyen Thanh Phat
- 22028027 - Ta Viet Hung

# References
The report of this project can be found [here](https://drive.google.com/file/d/1OFKHOi9O51qUSaPrAvEWhgV6bwBQ-DUj/view?usp=sharing)