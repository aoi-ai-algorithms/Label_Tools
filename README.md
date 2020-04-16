# Label_Tools
Software to perform boundary box labeling.
Reference: https://github.com/tzutalin/labelImg/tree/master/build-tools

### Dependencies
1. Anaconda

### Environment Setup
Installation step:
1. Follow the [steps](https://docs.anaconda.com/anaconda/install/windows/) to install the latest anaconda
2. Create a [python *3.6* environment ](https://docs.anaconda.com/anaconda/navigator/tutorials/create-python35-environment/) 
3. Open a terminal in that environment.

![alt text](https://github.com/HMFazleRabbi/Label_Tools/blob/master/doc/open_terminal.png "Start environment.")

4. cd inside the BBox_Label_Tool that you have cloned
5. run the labelImg.py using the following command

**python labelImg.py**

![alt text](https://github.com/HMFazleRabbi/Label_Tools/blob/master/doc/labelpy.png "cd and run labelImg.py")

### Label tools coordinate format
The label tool is designed to be used with YOLO (not Pascal) format where the label format is as follows

x1,y1,x2,y2,class