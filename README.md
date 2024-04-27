This bearing dataset is publicly available from the Laboratory for Internet of Things Sensing and Control at Hangzhou Dianzi University. 

This dataset was obtained from experiments simulating faults on PT500min bearings. It includes vibration acceleration data for ten types of bearing faults: Normal (N), Inner Race Fault (IF), Outer Race Fault (OF), Ball Fault (BF), Cage Fault (CF), Inner and Outer Race Compound Fault (IF&OF), Inner Race and Ball Compound Fault (IF&BF), Inner Race and Cage Compound Fault (IF&CF), Outer Race and Ball Compound Fault (OF&BF), and Inner and Outer Race and Ball Compound Fault (IF&OF&BF). The file format is .mat

Each type of bearing fault data contains two folders: 1.rpm1000_var_load: Contains data for seven different load forces at a fixed speed of 1000 rpm. The load forces are 0, 200, 400, 600, 800, 1000, and 1200 N. 2.var_speed_f600: Contains data for seven different speeds at a fixed load force of 600 N. The speeds are 400, 600, 800, 1000, 1200, 1400, and 1600 rpm.

Each folder for a specific operating condition contains 10 .mat files, representing ten data collections. The data sampling frequency of this experimental platform is 10 kHz, and the sampling time ranges from 20 to 25 seconds. Four vibration sensors are used for data collection, with data dimensions arranged in the order of 1-4 rows representing the motor, bearing base, bearing parallel upper end, and bearing parallel side end. Therefore, the data dimensions in each .mat file are (4, 200000+), where the first dimension corresponds to the four different vibration measurement positions mentioned above, each with over 200000 data points.

Due to the large size of the entire dataset, it is not convenient to download directly. We have provided Baidu Netdisk download links for each type of fault data. The table below shows each type of fault and its corresponding download link:

链接：https://pan.baidu.com/s/1ZwhtAA9kalHDKyBsD0RmvQ?pwd=DHUC 
提取码：DHUC
