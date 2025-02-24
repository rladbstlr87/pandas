# 새로운 프로젝트 시작하게 되면..
- python -m venv venv : 가상환경 생성
- source venv/Scripts/activate : 가상환경 활성화
- pip <module_name> : 모듈 설치 (jupyterlab, numpy, pandas)
- pip freeze >> requirements.txt : 현재 설치된 모듈 리스트 저장
# 컴터 용량문제로 venv 지웠다가 다시 설치할 일이 생기면...
- pip install -r requirements.txt : requirements.txt 기준으로 모듈설치
