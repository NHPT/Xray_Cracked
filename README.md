# xray Cracked

## Introduction

Since I was busy a while ago, I will upload the Xray crack version today. However, it is only for learning and testing. Do not use it for illegal attacks, or you will bear the consequences. This repositories will be deleted at any time.

## Method

Patch two key jumps (JL and JNZ) in the certificate verification function to bypass the verification.

## Result

### Listen  
1.9.8  
![](https://github.com/NHPT/Xray1.9.1/blob/main/img/1.9.8.png)
![](https://github.com/NHPT/Xray1.9.1/blob/main/img/1.9.8_2.png)

1.9.1  
![](https://github.com/NHPT/Xray1.9.1/blob/main/img/listen.png)

### Parameter x  
1.9.8  
![](https://github.com/NHPT/Xray1.9.1/blob/main/img/1.9.8_3.png)
![](https://github.com/NHPT/Xray1.9.1/blob/main/img/1.9.8_4.png)

1.9.1  
![](https://github.com/NHPT/Xray1.9.1/blob/main/img/port.png)

## Issues 

MAC OS cannot run Solution:

1. Execute the `uname -a` command to check whether the operating system architecture conforms to the Xray execute.

2. Execute the `chmod 755 xray_darwin_amd64` command to add execution permission to the program xray_darwin_amd64. Otherwise, the following information is displayed:

![](https://github.com/NHPT/Xray_Cracked/blob/main/img/unchmod.png)

3. Set permission in "Security and Privacy" ->"General".

![](https://github.com/NHPT/Xray_Cracked/blob/main/img/disp1.png)  
![](https://github.com/NHPT/Xray_Cracked/blob/main/img/set.png)  
![](https://github.com/NHPT/Xray_Cracked/blob/main/img/run.png)  
