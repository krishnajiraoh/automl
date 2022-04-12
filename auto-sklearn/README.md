# automl

# Installation:

## Install Brew:

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
https://automl.github.io/auto-sklearn/master/index.html

## Install Swig:

    brew install swig

## Install Auto-sklearn
    pip3 install auto-sklearn


## Docker

    docker pull mfeurer/auto-sklearn:master

    docker run -it -v ${PWD}:/opt/nb -p 10000:8888 mfeurer/auto-sklearn:master /bin/bash -c "mkdir -p /opt/nb && jupyter notebook --notebook-dir=/opt/nb --ip='0.0.0.0' --port=8888 --no-browser --allow-root"

    http://0.0.0.0:10000/