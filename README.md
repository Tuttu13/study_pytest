# study_pytest

# commands
- 仮想環境 active/deactivate
```python -m venv venv && source ./venv/Scripts/activate deactivate```
- 初回コンテナ作成
```docker-compose -f docker-compose.yml run app django-admin startproject study_pytest .```
- コンテナビルド
 ```docker compose -f docker-compose.prod.yml up -d```
- コンテナダウン
 ```docker-compose -f docker-compose.prod.yml down```