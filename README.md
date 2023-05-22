# Review-Classifier
This work is aimed at creating baseline models and drawing up a benchmark.
***
Metrics of the dataset's undersample models (embedded LaBASE (en)).
| Модель | Best F1 | Precision | Recall | train F1 | Precision | Recall | diff F1 |
| ------ | ------- | --------- | ------ | -------- | --------- | ------ | ------- |
| ReLU1 | 0.478 | 0.44 | 0.44 | 0.44 | 0.42 | 0.397 | 0.394 |
| ReLU2 | 0.492 | 0.44 | 0.44 | 0.44 | 0.414 | 0.384 | 0.383 |
| ReLU3 | 0.48 | 0.44 | 0.44 | 0.44 | 0.419 | 0.394 | 0.393 |
| CNN | 0.477 | 0.47 | 0.47 | 0.47 | 0.466 | 0.444 | 0.439 |
| LSTM 1 | 0.491 | 0.48 | 0.48 | 0.48 | 0.465 | 0.454 | 0.453 |
| LSTM 2 | 0.49 | 0.47 | 0.48 | 0.47 | 0.484 | 0.448 | 0.446 |
| Transformer | 0.444 | 0.44 | 0.44 | 0.42 | 0.378 | 0.362 | 0.339 |
___
Metrics of models of Russian reviews (rubert-tiny2).
| Модель | Best F1 | Precision | Recall | train F1 | Precision | Recall | diff F1 |
| ------ | ------- | --------- | ------ | -------- | --------- | ------ | ------- |
| ReLU1 | 0.51 | 0.53 | 0.53 | 0.52 | 0.498 | **0.496** | **0.487** |
| ReLU2 | 0.53 | 0.54 | 0.54 | 0.54 | 0.497 | 0.494 | 0.486 |
| ReLU3 | 0.521 | 0.51 | 0.52 | 0.51 | 0.479 | 0.482 | 0.473 |
| CNN | 0.502 | 0.52 | 0.52 | 0.51 | 0.499 | 0.477 | 0.475 |
| LSTM 1 | 0.519 | 0.5 | 0.51 | 0.5 | 0.499 | 0.471 | 0.471 |
| LSTM 2 | **0.535** | 0.54 | 0.54 | 0.54 | 0.501** | 0.479 | 0.48 |
| Transformer | 0.486 | 0.48 | 0.47 | 0.47 | 0.479 | 0.477 | 0.474 |
