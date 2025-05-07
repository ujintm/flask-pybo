# 배고파융..

이 프로젝트는 Flask 기반으로 만든 맛집 Q&A 게시판입니다.  
질문, 답변, 댓글, 사용자 로그인/회원가입 기능이 포함되어 있습니다.

---

## 📂 프로젝트 실행 방법

1. 레포 클론
```bash
git clone [레포주소]
cd [프로젝트폴더]

2. 가상환경 생성 및 활성화
python -m venv venv
source venv/bin/activate   # Windows는 venv\Scripts\activate

3. 필요 패키지 설치
pip install -r requirements.txt

4. 데이터베이스 초기화
flask db init
flask db migrate
flask db upgrade

5. 서버 실행
flask run
