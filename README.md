## Time Series IPCA

This project aims to analyze and predict the IPCA historical series. Challenge of the Time Series discipline of the postgraduate course in Artificial Intelligence.

#### Serie plot

<img align="center" alt="serie" src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/serie_plot.png" data-canonical-src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/serie_plot.png"  height="300" />

#### Lag plot

<img align="center" alt="lag-plot" src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/lag_plot.png" data-canonical-src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/lag_plot.png" width="600" height="300" />

#### Experiment with LSTM

<img align="center" alt="lstm experiment plot" src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/experiment_lstm.png" data-canonical-src="https://raw.githubusercontent.com/macio-matheus/time-series-ipca/master/docs/experiment_lstm.png" width="600" height="300" />

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
