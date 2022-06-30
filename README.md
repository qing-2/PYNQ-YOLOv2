来源 ： [dhm2013724/yolov2_xilinx_fpga](https://github.com/dhm2013724/yolov2_xilinx_fpga)  

> 因为规范更改，原本的tcl文件替换成了hwh。所以我用原作代码生成了IP再生成比特流文件，附带着就得到了hwh文件
> 因为规范更改，Xlnk不能用了，改用allocate

Weight and bias are available in 
Continue with the step of creating yolov2.tcl and yolov2.bit
1.  Open yolov2.ipynb in jupyter notebook
2. You can change the image path:  
```python
#image path
ORIG_IMG_PATH = 'dog.jpg'
```
3. You can also change the bitstream:(The name of .hwh must be same as the name of .bit)  
```python
overlay = Overlay("yolov2.bit")
```
4. Run all  
# Results as:  
![image1](https://github.com/dhm2013724/yolov2_xilinx_fpga/blob/150MHzTn4Tm32Tr26Tc26Cin4Cout2/pynq/result2.jpg)

