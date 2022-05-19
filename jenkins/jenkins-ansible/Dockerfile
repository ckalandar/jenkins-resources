FROM jenkins/jenkins

USER root

RUN apt -y update && \
    apt -y install python3 python3-pip

RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py && \
    python3 get-pip.py && \
    pip3 install ansible --upgrade

USER jenkins
