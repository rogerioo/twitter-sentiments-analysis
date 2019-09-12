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

**Fourth step:** open the *jupyter notebook* file
```
Twitter Sentiment Analysis.ipynb
```

**Fifth step**: Navigate to cell option and choose the option "Run All".

If you want to stop the running container, just press Ctrl + C and wait.

---

This project was developed as requirement to join GPAM (Grupo de Aprendizado de Máquina), a research group in machine learning of the University of Brasilia.
