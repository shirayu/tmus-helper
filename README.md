
# tmus-shell

Personal interactive shell for [tmsu](https://tmsu.org/)

## Usage

Launch the shell.

```sh
tmsu-shell -D /path/to/.tmsu/db
```

First input the file path with single quotes.
Then, its tags will be displayed with starts ``*``.

```txt
'/path/to/myfile'

  [1] Car
* [2] Face
  [3] Watch
```

- Add new tags with the numbers like ``3``
- Add new tags with the prefix ``!`` like ``!Game``
- Remove tags with the prefix ``u`` and a number like ``u1``
- Display current tags with ``l``
