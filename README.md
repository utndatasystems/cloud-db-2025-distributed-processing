# Distributed Query Processing

The task is to implement a shuffle- and broadcast-based two-way join algorithm.

The boilerplate is under `template`. Use `data_generator.py` to generate the two input relations.

```
python data_generator.py
```

To fire up two nodes, you can use `network.py`, started in two different terminal tabs:

```
python network.py 0 "[5555, 5556]"
python network.py 1 "[5555, 5556]"
```


