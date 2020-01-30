## Time Series IPCA

This project aims to analyze and predict the IPCA historical series. Challenge of the Time Series discipline of the postgraduate course in Artificial Intelligence.

#### Serie plot

<img align="center" alt="serie" src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/serie_plot.png" data-canonical-src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/serie_plot.png" width="400" height="200" />

#### Lag plot

![lag plot](https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/lag_plot.png)

#### Experiment with LSTM

![lstm experiment plot](https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/experiment_lstm.png)

### Usage
First of all, build the container using docker-compose and then you can 
access the Jupyter that is ready to be used.

#### Run with docker compose
```sh
cd time-series-ipca
docker-compose up -d
```

#### Accessing Jupyter
```sh
http://<your-ip>:8111/tree
```

#### Ports
```sh
    - 8111 => Jupyter
    - 6011 => Tensorboard
    - 5011 => App
```

### DockerHub
```sh
https://hub.docker.com/r/maciomatheus/jupyter_notebook_data_science/
```
