# CopyPasta

**Dead Simple Copy and Paste**

Copy or cut files, then paste them later. CopyPasta provides the commands `c`, `x`, `v`, `pasta` and `emptypasta`.

- `c`: **Copy**. Add file to the _copy_ list.
- `x`: **Cut**. Add file to the _cut_ list.
- `v`: **Paste**. Copy files on the _copy_ list and move files on the _cut_ list.
- `pasta`: View the _copy_ and _cut_ lists.
- `emptypasta`: Empty the _copy_ and _cut_ lists.

The copy and cut commands `c` and `x` accept filenames as parameters, or read them from standard input (or both). This makes them useful for handling piped output from commands like `find`.

## Usage
- `[c|x] file1, file2...`
- `[c|x] < list_of_filenames`
- `v`
- `[empty]pasta`

## Examples
- `find -name *.mp3 | x`
- `c *.tar.gz`
- `v`

## Install

[![basher install](https://www.basher.it/assets/logo/basher_install.svg)](https://www.basher.it/package/)

```shell
## To install this package with basher
basher install primatelab/copypasta
```