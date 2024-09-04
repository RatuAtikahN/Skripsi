# Website Sentiment Analisis Judul Berita

## Installation

1. Create Virtual Environment

```sh
python3 -m venv .venv
```

2. Activate Virtual Environment

```sh
source .venv/bin/activate
```

3. Go to directory src

```sh
cd src
```

4. Install requirements

```sh
pip install -r requirements.txt
```

5. Atur database, konfigurasi ada di .flaskenv

6. Jalankan Migration

```sh
alembic upgrade head
```

7. Running project

```sh
flask run
```
