# `gst_cli`
Generic-Shell-Toolbox cli tool for common shell operations, expandable with extensions

**Usage**:

```console
$ gst_cli [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--install-completion`: Install completion for the current shell.
* `--show-completion`: Show completion for the current shell, to copy it or customize the installation.
* `--help`: Show this message and exit.

**Commands**:

* `hello`
* `goodbye`

## `gst_cli hello`

**Usage**:

```console
$ gst_cli hello [OPTIONS] NAME
```

**Arguments**:

* `NAME`: [required]

**Options**:

* `--help`: Show this message and exit.

## `gst_cli goodbye`

**Usage**:

```console
$ gst_cli goodbye [OPTIONS] NAME
```

**Arguments**:

* `NAME`: [required]

**Options**:

* `--formal / --no-formal`: [default: no-formal]
* `--help`: Show this message and exit.
