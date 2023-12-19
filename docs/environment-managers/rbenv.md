# [rbenv](https://github.com/rbenv/rbenv)

`rbenv` is a version manager tool for the Ruby programming language on Unix-like systems.

# Common `rbenv` Commands

----

Install `rbenv` with Homebrew

```
$ brew update
$ brew install rbenv ruby-build
```

----

See the current `rbenv` version

```
$ rbenv --version
```

----

Install a new version of Ruby

```
$ rbenv install <version_tag>
```

----

See all installed versions of Ruby

```
$ rbenv versions
```

----

See the current version of Ruby being used in the session

```
$ rbenv version
```

----

Set the version of ruby that should be used in the current directory

```
$ rbenv local <version_tag>
```

----

Unset the local version of Ruby

```
$ rbenv local --unset
```

----

Set the global version of Ruby

```
$ rbenv global <version_tag>
```

----

See which executable will be run for the given `command`

```
$ rbenv which <command>
```

----

See which versions of Ruby have the executable for the given `command`

```
$ rbenv whence <command>
```
