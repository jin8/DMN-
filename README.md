README : To execute DMN*+
----------------------------

1. to train textual QA
python main.py --mode TEXT -- tasks #
or 
python main.py --tasks #


2. to test textual QA (Require DAQUAR dataset)
preprocess is necessary need to run 
preprocess_daquar(data_dir) function in read_image_data.py


python main.py --mode TEXT --test True

3. to train visual QA (Require COCO train2014, test2014, val2014 dataset)
python main.py --mode IMAGE


4. to test visual QA
python main.py --mode IMAGE --test True

5. to train image descriptor
python main.py --mode IMAGE_DESC


