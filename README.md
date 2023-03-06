# Labelme_to_YOLO
Small notebook for converting lableme json annotations to YOLO txt format
#### Usage

Just change input and output dirs: 

```python
INPUT_JSON_DIR = "examples_data/input_labelme/"  # Path to labelme annotations.
OUTPUT_TXT_DIR = "examples_data/output_yolo/"  # Path to output txt dir
```

Optionally fill ```python label_dict = {}``` to have desired label/number pairs. e.g. ```python label_dict = {'car': 0, 'person': 1,...}``` 
