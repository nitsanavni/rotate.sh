# rotate.sh

A simple rotation timer.

It opens itself (the script file) in the editor every X seconds.

The typist then moves the "typing" indicator one line down.

George is typing:

```
# John
# -- typing ---->
# George
# Ringo
# Paul
```

And now Ringo is typing:

```
# John
# George
# -- typing ---->
# Ringo
# Paul
```

## Usage

```shell
./rotate.sh
```

## Customize

One minute rotations, `code` editor:

```shell
./rotate.sh 60 code
```

Or:

```shell
§
```
