# React-Django

---

### 리액트 - 장고 연습용 사이드 프로젝트

- 주요 사용 기술 : Django REST Framework (DRF), React.js, MongoDB Atlas
- 프로젝트 상세 내용 : 미정

---

- 설정시 주의점
    1. CORS 에러 때문에 백 서버, 프론트 서버 포트 설정을 맞출 필요가 있음 (현재 백은 8000번 포트, 프론트는 3000번 포트)
    2. Pymongo와 djongo가 버전에 따라 서로 호환이 안 되어서 호횐되는 버전으로 맞춰야 함 (현재 Pymongo 버전은 3.12.3, djongo 버전은 1.3.6)
    3. Django의 기본 DB 설정은 로컬 DB에 연결하도록 되어 있기 때문에 클라우드 DB에 연결하기 위해서는 별도의 설정이 필요함

---# react_django_be
