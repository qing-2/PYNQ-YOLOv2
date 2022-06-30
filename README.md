来源 ： [dhm2013724/yolov2_xilinx_fpga](https://github.com/dhm2013724/yolov2_xilinx_fpga)  

> 因为规范更改，原本的tcl文件替换成了hwh。所以我用原作代码生成了IP再生成比特流文件，附带着就得到了hwh文件<br/>
> 因为规范更改，取消了分配空间的Xlnk类，改用allocate类

### 1.  Open yolov2.ipynb in jupyter notebook
### 2. You can change the image path:  
```python
#image path
ORIG_IMG_PATH   = './pictures/10.jpg'
```
### 3. You can also change the bitstream:(The name of .hwh must be same as the name of .bit)  
```python
overlay = Overlay("yolov2.bit")
```
### 4. Run all  
 
![image1](https://github.com/qing-2/PYNQ-YOLOv2/blob/master/output.jpg)

