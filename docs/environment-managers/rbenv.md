# [rbenv](https://github.com/rbenv/rbenv)

`rbenv` is a version manager tool for the Ruby programming language on Unix-like systems.

# Common `rbenv` Commands

----

Install `rbenv` with Homebrew

```console
$ brew update
$ brew install rbenv ruby-build
```

----

See the current `rbenv` version

```console
$ rbenv --version
```

----

Install a new version of Ruby

```console
$ rbenv install <version_tag>
```

----

See all installed versions of Ruby

```console
$ rbenv versions
```

----

See the current version of Ruby being used in the session

```console
$ rbenv version
```

----

Set the version of ruby that should be used in the current directory

```console
$ rbenv local <version_tag>
```

----

Unset the local version of Ruby

```console
$ rbenv local --unset
```

----

Set the global version of Ruby

```console
$ rbenv global <version_tag>
```

----

See which executable will be run for the given `command`

```console
$ rbenv which <command>
```

----

See which versions of Ruby have the executable for the given `command`

```console
$ rbenv whence <command>
```
