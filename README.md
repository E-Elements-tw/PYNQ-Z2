# E-Elements_labs PIP INSTALL Package

PYNQ-Z2��@�d�� 

- ��@�@ : �B�Φh���j��B�� 
- ��@�G : ��{�n�����ܾ�
- ��@�T : ��{OpenCV�v���B�z
- ��@�| : ��{�Y�ɤH�y�����z



## Quick Start

�N��@�d�Ҧw�˨�PYNQ�A�Х��s����PYNQ-Z2�}�o���A���}�׺ݨ���J�G

```
sudo pip3 install git+https://github.com/E-Elements-tw/PYNQ-Z2.git (on PYNQ v2.3)
sudo pip3.6 install git+https://github.com/E-Elements-tw/PYNQ-Z2.git (on PYNQ v2.2 and earlier)
```

# PYNQ-Z2 Hardware design rebuilt

���صw��]�p�A�N�d���ɮפU����w�ˤFVivado Design Suite���������]�ϥ�2018.2�����^�C ���Ӥ��B�����i��ާ@�G

1.�U���ø����Y�ɮר�A���q��:https://github.com/E-Elements-tw/PYNQ-Z2.git

2.�}��Vivado Design Suite�n��A�bTcl Console��J:
```
  cd <�d���ɮ׸��|>/PYNQ-Z2-master/E_Elements_labs/src/Pynq-Z2/  
```
3.�M�׸��|�إߩһݪ�IP�A�bTcl Console��J:
```
  source ./build_base_ip.tcl
```
4.�إ߹�@�M��: 

     �� ��@�@ (�B�Φh���j��B��)�A�bTcl Console��J:
  
      source ./lab1.tcl 
```
     
     �� ��@�G (��{�n�����ܾ�)�A�bTcl Console��J:
   
      source ./lab2.tcl 
``` 
 
     �� ��@�T (��{OpenCV�v���B�z)�A�bTcl Console��J:      
 
      source ./lab3.tcl 
```
