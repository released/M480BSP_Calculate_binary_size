# M480BSP_Calculate_binary_size
 M480BSP_Calculate_binary_size


update @ 2023/12/26

1. use sct file , to calculate binary size

refer to link : https://blog.csdn.net/booksyhay/article/details/106556326

2. below is KEIL LINKER setting ( load image.sct file )

![image](https://github.com/released/M480BSP_Calculate_binary_size/blob/main/KEIL_Linker.jpg)
	
3. below is KEIL TARGET setting and sct file 

![image](https://github.com/released/M480BSP_Calculate_binary_size/blob/main/KEIL_sct.jpg)
	
4. below is log result 

- ROM size : Code + RO + RW

- RAM size : RW + ZI

![image](https://github.com/released/M480BSP_Calculate_binary_size/blob/main/log.jpg)



