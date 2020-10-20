# water-scheduling-paddy-novnc-dosbox-lotus123
Docker Water issue Scheduling software for Paddy based on rotational water issue with fixed time table  and variable discharge 

# Docker Water issue Scheduling software for Paddy based on rotational water issue with fixed time table  and variable discharge 

DOSBox from https://www.dosbox.com/

Lotus123/Dos from https://vetusware.com/manufacturer/Lotus%20Software/?author=86

noVNC  from : Joel Martin (github@martintribe.org).  https://novnc.com/info.html 
 
The above software have been used to create in this  docker image , with pre-installed  Lotus123 & Water Scheduling Software for Paddy on DOSBox 




Introduction:-

The water issue scheduling software incorporated in this docker repository has been  used in preparation and monitoring of  water issue schedules for Paddy cultivation in Krindi Oya Irrigation Project Sri Lanka successfully in the year 1988 .The water issue schedules were prepared  based on field>distributory>branch>main canal level rotation. The scheduling software package has been created using Lotus123 with macro programs. In this software the water issue schedules are prepared with definite opening and closing time table of the field canal off take gates  such that the farmers can easily adhere in to it . It is based on fixed water issue duration and variable discharge depending on the stage of crop . The rotational time table can not be adopted during the land preparation period as the water requirement is high . Therefore continuous discharge is issued for land preparation.Although this software was designed for In Kirindi Oaya Irrigation project , it can be adopted to any other project of  similar nature , with minor adjustments. 

You can get more details on the software from the following document presented in 1988 for  the annual sessions in the Institution of Engineers , Sri Lanka by the author.

https://github.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/blob/main/koisp.pdf


For more details please see this video - 


Usage :-
 

To create Water Scheduling Software for Paddy  using bkjaya1952/water-scheduling-paddy-novnc-dosbox-lotus123
Refer:- 

https://hub.docker.com/r/bkjaya1952/water-scheduling-paddy-novnc-dosbox-lotus123

On the Ubuntu terminal

<code>sudo docker create -t -p 8008:8080 --name dos123 --privileged=true bkjaya1952/water-scheduling-paddy-novnc-dosbox-lotus123</code>

<code>sudo docker start dos123</code>

<code>xdg-open http://localhost:8008/vnc_lite.html</code>

<img src="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-20%2017-37-58.png" alt="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-20%2017-37-58.png" width="625" height="520">

Figure :- 1 Flow Chart of the Scheduling Process using FARM.WK1 ,  CORE.WK1, and CHITRA.WK1

<img src="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-18%2017-32-57.png" alt="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-18%2017-32-57.png" width="625" height="520">

Figure :- 2 Calculating Crop Water requirement using FARM.WK1

<img src="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-18%2017-32-57.png" alt="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-18%2017-32-57.png" width="625" height="520">

Figure :- 3 Scheduling using CORE.WK1

<img src="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-18%2017-34-07.png" alt="https://raw.githubusercontent.com/bkjaya2020/water-scheduling-paddy-novnc-dosbox-lotus123/main/Screenshot%20from%202020-10-18%2017-34-07.png" width="625" height="520">

Figure :- 4 Computing dischrge at the Sluice using CHITRA.WK1

Plese refer https://bkjaya.wordpress.com/2020/10/12/how-to-install-docker-water-issue-scheduling-software-for-paddy-based-on-rotational-water-issue-with-fixed-time-table-and-variable-discharge-on-ubuntu-20-04/

