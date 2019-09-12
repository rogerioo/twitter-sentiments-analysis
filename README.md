# Twitter Sentimental Analysis

## About

This project aim to classify tweets, compiled in a dataset provided from [kaggle](https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech) and tells if they are neutral ou hated speech. To do so, it's used some techniques of natural language process.

To simplify the usage you can use the docker-compose structre, that's already defined in my [github](https://github.com/rogerioo/twitter-sentiments-analysis) repository and the image build on [dockerhub](https://cloud.docker.com/u/rogerioo/repository/docker/rogerioo/twitter-sentiments-analysis).

## Usage

Pre-requirements: [Docker](https://docs.docker.com/install/linux/docker-ee/ubuntu/)

**First step:** clone the [repository](https://github.com/rogerioo/twitter-sentiments-analysis)  to you computer
```sh
$ git clone git@github.com:rogerioo/twitter-sentiments-analysis.git
```

**Second step:** login into you dockerhub account
```sh
$ docker login
```

**Third step:** inside the root of the folder, start docker
```sh
$ sudo docker-compose up
```

**Fifth step:** click on the following link
![link](https://github.com/rogerioo/twitter-sentiments-analysis/blob/master/link.png)

**Sixth step:** open the *jupyter notebook* file
![file](https://github.com/rogerioo/twitter-sentiments-analysis/blob/master/file.png)

**Seventh step**: Navigate to cell option and choose the option "Run All".
![run](https://github.com/rogerioo/twitter-sentiments-analysis/blob/master/run.png)

If you want to stop the running container, just press Ctrl + C on *terminal* and wait.

---

This project was developed as requirement to join GPAM (Grupo de Aprendizado de Máquina), a research group in machine learning of the University of Brasilia.
