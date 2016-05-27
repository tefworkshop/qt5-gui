FROM tefworkshop/qt5-console:8
MAINTAINER Stefan Hans <stefan.hans@telefonica.com> 

RUN mkdir /home/HelloWorldGui
ADD HelloWorldGui.pro /home/HelloWorldGui
ADD main.cpp /home/HelloWorldGui
ADD mainwindow.cpp /home/HelloWorldGui
ADD mainwindow.h /home/HelloWorldGui
ADD mainwindow.ui /home/HelloWorldGui

#RUN cd /home/HelloWorldGui && qmake && make && ./HelloWorldGui

CMD ["/bin/bash"]
