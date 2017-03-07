Ghosts in The Shell
===================

GITS is a repository of presentation and tutorials about Machine Learning, and perhaps Artificial Intelligence at large.

The repository is structured as a collection of mostly independent projects.

## Setup
### Automated

* Python 3.6

From the home directory:

```
$ ./setup
```

When you open a new shell, you need to activate the right `virtualenv`. By default, thismeans running the following command:

```
$ source ~/tmp/gits/bin/activate
$ jupyter notebook
```

If you want to choose the `virtualenv` name or else, please refer to the [Manual, with Virtualenv] section.

### Manual, with Virtualenv

* Python 3.6
* Virtualenv

From the home directory:

```
$ virtualenv --python python3.6 ~/tmp/gits
$ source ~/tmp/gits/bin/activate
$ pip install -r requirements.txt
$ jupyter notebook
```

When you open a new shell, you need to activate the right `virtualenv`. By default, thismeans running the following command:

```
$ source ~/tmp/gits/bin/activate
$ jupyter notebook
```

### Manual, plain

* Python 3.6
* PyPI a.k.a. `pip`, for this version of the Python interpreter.

From the home directory:

```
$ pip install -r requirements.txt [--user]
$ jupyter notebook
```

---
Made with the support of [Chikaku](https://www.chikaku.co.jp/) and the Chikaku Team. 🍵
