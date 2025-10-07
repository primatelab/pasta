# Pasta

**Dead Simple Copy and Paste**

Copy or cut files, then paste them later. `pasta c` and `pasta x` add files to copy or paste lists, then `pasta v` pastes them.

## Usage
- `pasta [c|x|v|e] file1, file2...`
- `pasta [c|x|v|e] < list_of_filenames`
- `pasta v`

## Options

- **c|copy**: Add file to the _copy_ list.
- **x|cut**: Add file to the _cut_ list.
- **x|cut**: Copy files on the _copy_ list and move files on the _cut_ list.
- **e|empty**: Empty _copy_ and _cut_ lists.

## Install

[![basher install](https://www.basher.it/assets/logo/basher_install.svg)](https://www.basher.it/package/)

```shell
## To install this package with basher
basher install primatelab/pasta
```

## Aliases

I suggest adding the following aliases to your `.bashrc` file:
```shell
alias c='pasta c'
alias x='pasta x'
alias v='pasta v'
```

## Examples
- `find -name *.mp3 | x`
- `c *.tar.gz`
- `v`
