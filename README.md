This script was originally written by by [Guilherme Prokisch](https://github.com/guilhermeprokisch) as a contribution to [Serenata de Amor](https://github.com/datasciencebr/serenata-de-amor). This repo was set just for a _collective programming_ event focused on refactoring and optimizing it.

**Requirements**

* [Python](https://python.org) — _don’t ask me the version: this is 2016 (almost 2017!…)  so take your best guess_ ; )
* A [Google Places API](https://developers.google.com/places/web-service/get-api-key) key added to a file named `config.ini` (take `config.ini.example` as a reference)
* A bunch of stuff installed with `$ python -m pip install -r requirements.txt`
* [This dataset](https://s3-sa-east-1.amazonaws.com/serenata-de-amor-data/2016-09-03-companies.xz) downloaded into `data/` directory

**Running**

To use the full dataset (+60k companies) use:

```python
$ python sex_places.py
```
To use a sample of the dataset add a number after the command. For example this will run with only 42 companies:

```python
$ python sex_places.py 42
```

**New local to get Dataset**
* [This dataset](https://github.com/okfn-brasil/serenata-de-amor/blob/master/contrib/data/companies_sample.xz)
