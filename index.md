---
layout: default
---
# DeepSchool.io

A community to learn Deep Learning for Free! Democraticise AI. This is a self contained set of Python Notebooks of Deep Learning Tutorials + more!

## Goals
1. Make Deep Learning easier (minimal code).
2. Minimise required mathematics.
3. Make it practical (runs on laptops).
4. Open Source Deep Learning Learning.
5. Grow a collaborating practical community around DL.
6. Memes: No seriously. Make DL fun and interactive, this means more Trump tweets.

## Support Us
There's a few ways you can support this initiative:
1. Right now this is very much a self funded project. If you wish to see more and more high quality tutorials and videos support us at: https://www.patreon.com/deepschoolio
2. Subscribe to our [YouTube channel here](http://www.youtube.com/user/sachinabey?sub_confirmation=1).
3. Star this repository and share it!
4. Pull requests. This is a community effort after all.

## Contents
The following contents are each contained within a folder:
1. Data Science (eg. Pandas)
2. Deep Learning (Keras + Tensorflow)
3. Bayesian Learning (PyMC3)

## Installation
If you are a beginner (haven't done CNNs yet) simply click [this link](https://mybinder.org/v2/gh/sachinruk/deepschool.io/master) instead of following the installation comands below. It launches a live notebook server with these notebooks using [binder](https://beta.mybinder.org/): [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/sachinruk/deepschool.io/master)
1. Install Docker https://www.docker.com/
2. Use the following commands to run from docker<sup>[1](#myfootnote1)</sup>.
```
git clone https://github.com/sachinruk/deepschool.io.git
cd deepschool.io
bash run.sh
```
3. Now go to `localhost:9000` on your browser to start using the jupyter notebooks.
4. (Optional) If you are on a mac/windows some of the examples may not work because the docker image may run out of memory. Hence under preferences in docker there is the option to increase the allocated memory. I have set it to 8GB. Run `bash run.sh` again if you reset memory.

See [here](./misc/windows_instructions.md) for installing on windows.

## Support
You can ask questions and join the development discussion:
- On the [DeepSchool-io Google group](https://groups.google.com/forum/#!forum/deepschoolio). **Long detailed questions go here**.
- On the DeepSchool-io Slack channel. Use [this link](https://intense-waters-64607.herokuapp.com/) to request an invitation to the channel.

## Meetup
First meetup node:
https://www.meetup.com/DeepSchool-io/

## YouTube playlist
Find the corresponding video tutorial here (not all notebooks have an associated video)
https://www.youtube.com/playlist?list=PLIx9QCwIhuRS1SPS9LHF7VjvZyM1g2Swz