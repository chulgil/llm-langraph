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

### .env 환경설정파일

> 프로젝트 폴더에 .env파일 생성한 후 아래 인증정보 넣기

```bash

OPENAI_API_KEY=본인인증키
PINECONE_API_KEY=본인인증키
UPSTAGE_API_KEY=본인인증키
LANGCHAIN_API_KEY=
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=default
LANGSMITH_PROJECT=default
LANGSMITH_API_KEY=본인인증키
LANGSMITH_ENDPOINT=https://api.smith.langchain.com
TAVILY_API_KEY=본인인증키

```