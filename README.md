# jupyter-notebook
## Usage

- パスワード設定
  - `docker-compose.yml`のJUPYTER_PASSを変更(default: password)

- 起動

```
docker-compose up -d
```

- その他

hostからコンテナに渡したいデータがある場合は./dataに格納。
host側の`./ipynb/`は`/home/jovyan/work`にマウントされている。
`./data`と`./ipynb`は適切にpermissionをつけてください。
`./notebook`に作成済みnotebookが格納されている。


**`./data`と`./ipynb`は`gitignore`に含まれているので注意**

## 中身

jupyter/datascience-notebookベース
追加で必要なものがあれば`./jupyter/requirements.txt`に追記


