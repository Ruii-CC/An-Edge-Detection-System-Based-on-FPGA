# An-Edge-Detection-System-Based-on-FPGA
这是中南大学工程实践Ⅰ的选题：基于FPGA的边缘检测系统，并在此基础上进行了额外的拓展。

# Brief
本项目基于ov5640+sobel边缘检测工程开发，添加roberts、prewitt、canny、laplacian算子，中值滤波，二值化，红外遥控控制，lcd屏幕字符显示，蜂鸣器，led。
roberts和laplacian算子之前有二值化处理，以减少显示出来的噪声。红外遥控上下键可以增加、减少阈值，回车键控制是否切换灰度图像，0键控制是否进行滤波处理，1~5键分别代表五种算法。阈值可以动态调整，lcd屏幕左上角会显示当前模式、是否开启滤波和当前阈值。阈值超出限制会蜂鸣报警和led常亮。最后，实现了一种定量评估指标。
# Stracture
rtl文件夹放有工程源码，sim文件夹放有仿真代码
# Video
视频演示会同步上传到B站。

