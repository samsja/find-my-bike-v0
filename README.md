# find_my_bike

## How to use it ?

first install the dependecies:

```shell
poetry install
```

only for development: 


add the precommit hook

```
poetry run pre-commit install
```

sync the notebook (only once)

```
poetry shell
make notebook-sync
```

## launch a jupyter lab session

```shell
poetry run jupyter lab
```

## Use tensorboard

```shell

poetry shell
make tensorboard
```

## Format the code without the precommit hook

```shell
poetry shell
make formatting
```

## Tests:

to run the tests:

```shell
poetry shell
make tests
```


This porject has been generated by samsja [boilerplat](https://github.com/samsja/pytorch-boilerplate)
