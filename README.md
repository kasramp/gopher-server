# Gopher Server

A simple Gopher Server built on top of [Pituophis](https://github.com/dotcomboom/Pituophis).

## How to run

First create a virtual env:

```bash
$ python3 -m venv venv
```

Then activate it,

```bash
$ source env/bin/activate
```

Install the dependencies:

```bash
$ pip3 install -r requirements.txt
```

Finally, run the server:

```bash
$ python3 server.py
```

To access the server, you need a Gopher capable browser such as Lynx or [Gophie](https://gophie.org/).
Once you have that in place, open `gopher://127.0.0.1:/7070` and you should see the home page.

To modify the content, just go to the `home_page` directory and apply the changes.

A good place to learn about gopher page syntax if you are not familiar with it, [here](https://github.com/sgolovine/roll-your-gopher).

To deactivate virtual environment:

```bash
$ deactivate
```

## Useful commands

Generate `requirement.txt` file:

```bash
$ pip3 freeze > requirements.txt
```

To install from the dependency file:

```bash
$ pip3 install -r requirements.txt
```
