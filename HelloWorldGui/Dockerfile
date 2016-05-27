FROM tefworkshop/qt5-console
MAINTAINER Stefan Hans <stefan.hans@telefonica.com> 

RUN mkdir /home/HelloWorldGui
ADD main.cpp /home/HelloWorldGui
ADD mainwindow.cpp /home/HelloWorldGui
ADD mainwindow.h /home/HelloWorldGui
ADD mainwindow.ui /home/HelloWorldGui

#RUN cd /home/HelloWorldGui && qmake -project && qmake && make && ./HelloWorldGui

CMD ["/bin/bash"]
