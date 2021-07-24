# Federated learning

## What is Federated learning?
<b>Federated learning is a machine learning technique that trains an algorithm across multiple decentralized edge devices or servers holding local data samples, without exchanging them.</b> This approach stands in contrast to traditional centralized machine learning techniques where all the local datasets are uploaded to one server, as well as to more classical decentralized approaches which often assume that local data samples are identically distributed.

<p align="center" width="100%">
    <img width="500" height="300" src="https://media.giphy.com/media/T76Kv4v01s07HMQiKC/giphy.gif"> 
</p>

The animation above illustrates the steps invloved in the federated learning approach which are as follows:<br>
1) At first the model parameters of the global model are used are used as an initial state by clients.
2) Now the clients train their local model with their respective local data.
3) After that the new model parameters obtained from all the clients are aggregated using various aggregation strategies
4) The final aggregated model parameters are given back to the central server.
5) This process is repeated iteratively untill a pre-defined criteria is met (e.g. a maximum number of iterations is reached or the model accuracy is greater than a threshold).
