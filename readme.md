# segment pills

**Install**
1. Install Keras Mask-RCNN (https://drive.google.com/file/d/1Ug6697XbnRpEPjZyN5uLEEHyR27JyeVo/view?usp=sharing)
2. Create sym-link: (e.g. ln -s ~/Mask_RCNN/mrcnn mrcnn)
3. Download the pre-trained network and place it in the main directory: https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5


## Project structure
```
    |--- mask_rcnn
    | |--- pills/
    | | |--- images
    | | |--- via_region_data.json
    | |--- pills.py
    | |--- mask_rcnn_coco.h5
    | |--- mrcnn/
```


## Investigate
```python pills.py --mode investigate```

## Train
```python pills.py --mode train```

## Predict
```python pills.py --mode predict --image examples/pills_01.jpg --weights logs/pills20200717T1421/mask_rcnn_pills_0010.h5```

**OUTPUT 1:**\
![Alt text](readme/output_pills_01.png?raw=true "Title")

**OUTPUT 2:**\
![Alt text](readme/output_pills_02.png?raw=true "Title")

**OUTPUT 3:**\
![Alt text](readme/output_pills_03.png?raw=true "Title")
