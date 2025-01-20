# Multi-Agent Guideline

## Environment

1. Homebrew 설치
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. minconda 설치 
```bash
brew install miniconda
```

conda 환경 초기화
```bash
# 아래 명령어 수행 후 Shell 재실행
conda init
```

3. Autogen 을 위한 Conda 환경 생성
```bash
# 환경 생성
conda create --name autogenstudio python=3.11

# 환경 활성화
conda activate autogenstudio
```

4. AutogenStudio 설치
```bash
pip install autogenstudio
```

