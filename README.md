# llm-langraph


## 설치

### 가상환경 설정
```bash

python -m venv .venv

source .venv/bin/activate

which python
python --version

```

### 설치된 버전 파일에 저장
```bash

pip freeze > requirements.txt

```

### Jupyter에서 현재 가상환경을 `llm-langraph`이름으로 커널 등록하는 방법

```bash
source .venv/bin/activate
pip install ipykernel
python -m ipykernel install --user --name=llm-langraph --display-name "Python (llm-langraph)"



```

- 이후 .ipynb에서 사용방법은 : 상단메뉴에서
- Kernel → Change kernel → Python (llm-langraph)