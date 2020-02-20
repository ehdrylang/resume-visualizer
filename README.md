# resume-visualizer
Tools for visualizing developer's resumes

# overview
개발자가 이력서와 포트폴리오를 작성하는 일은 흔한 일이다. 
그 만큼 자주 있는 일인 이력서와 포트폴리오 작성을 **쉽게 작성하도록 가이드하고**, **경험과 학습을 한 눈에 알아볼 수 있도록 그림으로 표현**해주는 프로그램을 위한 프로젝트다.


# design
- 기술 스택과 관련된 이미지는 구글 드라이브에 미리 구축해두고 사용한다.
- 구글 드라이브 이미지를 못 받아올 경우를 대비하여 각 기술 스택 이미지를 제공하는 홈페이지 링크를 파일로 관리하여 제공한다.
- time line을 그리기 위한 summary를 파싱할 수 있어야 한다.
- 프로젝트 정보는 개별 페이지로 제공할 수 있어야 한다.

# how to use
### just 3 steps
1. create a file(resume.md) in your Github Repository
2. run web application
  > `java -jar resume-visualizer.jar https://github.com/{username}/{your-repsitory}/blob/master/resume.md`
3. go to homepage (index.html)
  > `http://localhost:8080`
  
# resume.md guide
### coming soon...
