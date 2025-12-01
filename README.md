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

# Setup

1. Create a copy of the template (`template`), please name your group folder accordingly.
   ```bash
   cp -rf template my-awesome-team
   ```
1. Check in:
   ```bash
   git add my-aweseome-team
   git commit -m "updated my-aweseome-team"
   git fetch && git rebase origin/main && git push origin main
   ```