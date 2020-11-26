# Docker_task7.2-b-
Setting up python interpreter and running python code on docker container.
First of all i have to start docker service by using command:-
systemctl start docker
![](1.png)

Then i have to launch a docker container by using command:-
docker run -it --network host --name myos centos:latest
![](2.png)

To install python interpreter in container used command :- yum install python3

![](3.png)

I have successfully installed python interpreter

![](4.png)

Then i try to run python interpreter and run code of python.

![](5.png)

Finally, i run successfully python code on docker container.

Thank you !


