FROM sousouc/cmakeessential
MAINTAINER Sousouc "lucas.barros@hotmail.fr"

#import from the sousouc'github the source code
RUN apt-get install wget
RUN apt-get install nano
RUN mkdir home/code/
RUN wget https://github.com/sousouc/CodeC/raw/master/utilzreg-code.tar -O home/code/code.tar
RUN tar xvf home/code/code.tar

RUN wget https://raw.githubusercontent.com/sousouc/CodeC/master/bash.sh -O home/code/bash.sh
RUN chmod a+x /home/code/bash.sh

#import images 
RUN mkdir home/code/images
RUN wget https://github.com/sousouc/images/raw/master/DB2_MMRR-21-10.nii -O /home/code/images/DB2_MMRR-21-10.nii
RUN wget https://github.com/sousouc/images/raw/master/DB2_MMRR-21-11.nii -O /home/code/images/DB2_MMRR-21-11.nii
