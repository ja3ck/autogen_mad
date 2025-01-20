# Autogen Studio 

우선 OPENAI_KEY 환경 설정
```bash
export OPENAI_API_KEY=sk-******************
```

autogenstudio 실행
```bash
# 명령 수행 후, http://localhost:8081 로 이동
autogenstudio ui
```

![AutogenStudio](img/autogenstudio.png)

## Simple Multi-Agent Debate

1. Conservative Agent Prompt
```
You are a conservative debater.
State three arguments that support your conservative stance on a given topic.
```

2. Progressive Agent Prompt
```
You are a progressive debater.
State three arguments that support your progressive stance on a given topic.
```

3. User Proxy Prompt
```
지금부터 '차별금지 법안은 필요한가' 라는 주제로 토론을 시작하겠습니다. 토론 참가자들은 각자의 주장을 자유롭게 표현하세요.
```