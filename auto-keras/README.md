https://autokeras.com/docker/


# Installation:

    python3 -m pip install git+https://github.com/keras-team/keras-tuner.git
    python3 -m pip install autokeras


# Docker:

    docker pull haifengjin/autokeras:latest

    docker run -it --shm-size 2G haifengjin/autokeras /bin/bash

    docker run -it -v ${PWD}:/opt/nb -p 10001:8888 haifengjin/autokeras /bin/bash -c "mkdir -p /opt/nb && jupyter notebook --notebook-dir=/opt/nb --ip='0.0.0.0' --port=8888 --no-browser --allow-root"

    docker run -it -v ${PWD}:/opt/nb -p 10001:8888 my_auto_keras /bin/bash -c "mkdir -p /opt/nb && jupyter notebook --notebook-dir=/opt/nb --ip='0.0.0.0' --port=8888 --no-browser --allow-root"

    http://0.0.0.0:10001/


