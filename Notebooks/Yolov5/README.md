# This notebook includes code to:
    - Train a customized Yolov5 on LPCV.ai data
    - Train a customized Yolov5 on KITTI data
    - Export YOLOv5 for Edge delpoyment

- It is best to run the notebooks in a Google Colab environment
- To train on any dataset, the first cell must be run before any other

- To train on the LPCV.ai data from the challenges files:
  - If you do not have a zip file of the LPCV data in image and label format, you must upload all LPCV.ai videos and csv files before running all cells in succession. If you possess such a zip file, unzip the folder and run the cells beginning with the data augmenation cells.

In any cell with the command !python detect.py, different versions of the model can be run after they have been created by changing "./runs/train/exp/weights/best.pt" to the correct path to the new model file

- Headings exist within notebooks to explain workings of code
