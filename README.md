# Project Title
MANE 4280U-Robotics-Course

![alt text](https://github.com/Abdul-UOiT/4280U-Robotics-Course/blob/master/Selection_026.jpg)

## Getting Started
This repository provides the essential documentation and getting-started instructions. The system was tested with ```V-REP_PRO_EDU_V3_4_0_Linux``` and ```O.S./Linux/Ubuntu 16.04 LTS```. It should be also running with Windows and Mac.

/Note:```the following instructions for Linux user```, however it should be similar to another O.S. user (Windows and Mac).

### Prerequisites


* Download from [V-REP](http://www.coppeliarobotics.com/previousversions.html). Make sure to use this version[```V-REP 3.4.0 PRO EDU```]. Extract the file ```zip``` into home directory.


* Open the [Project Link](https://github.com/Abdul-UOiT/4280U-Robotics-Course.git), and download it from ```clone or download```

       OR open a terminal and type 

```cd ~```


```git clone https://github.com/Abdul-UOiT/4280U-Robotics-Course.git```

Now, you should have two folders: 1-```V-REP``` and 2-```4280U-Robotics-Course-master```


## Running the test

Make sure you are in the right directory. Open a terminal and navigate to the extracted folder of V-REP and run it by: 

```cd ~```

```cd V-REP_PRO_EDU_V3_4_0_Linux```

```./vrep.sh```

You will have the main window of V-REP with empty scene, open new scene from the upper-left-side bar, 

```file--->open scene--->/path/to/4280U-Robotics-Course-master/scene/simulation-robotics-course.ttt```

Open new terminal and run the test python file ```create_obj.py```

```cd ~```

```cd 4280U-Robotics-Course-master```

```python create_obj.py```




