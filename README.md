# blog2.data.gouv.fr

An attempt for an uncluttered Pelican (harder than expected…)

## 1. Install

Make a virtualenv

```shell
$ python3 -m venv venv
```

Install dependencies

```shell
$ source venv/bin/activate
$ pip install -r requirements.pip
```


## 2. Write

Within `content` folder.
Only `Title` and `Date` metadata are required.


## 3. Generate

```shell
$ make html serve
```

Open [http://localhost:8000/](http://localhost:8000/)


## 4. Iterate

And enjoy!
