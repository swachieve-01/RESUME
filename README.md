# Resume Web Page

프론트엔드 개발자를 목표로 하며 제작한 개인 이력서 웹 페이지입니다.  
단순한 정적 페이지 구현을 넘어,  
**PC와 테블릿, 모바일 환경에 맞는 레이아웃 설계와 반응형 구현 경험**을 중심으로 작업했습니다.

---

## 🔗 Demo
- GitHub Pages: https://swachieve-01.github.io/RESUME/
- Repository: https://github.com/swachieve-01/swachieve-01

---

## 🎯 Project Goal


- 이력서를 웹 환경에 맞게 구조화하기
- 정보의 가독성과 우선순위를 고려한 레이아웃 설계
- PC / Tablet / 모바일 환경에서 각각 자연스럽게 동작하는 반응형 구현
- “왜 이렇게 만들었는지”를 설명할 수 있는 코드 작성

---

## 🎨 Design Concept

- **Tone & Mood**  
  - 흑백 기반의 다크 테마
  - 장식을 최소화하고 콘텐츠 중심의 디자인

- **Target User**  
  - 신입 프론트엔드 개발자를 검토하는 채용 담당자

- **Layout Idea**  
  - PC: 3컬럼 그리드 구조  
    (콘텐츠 / 분리선 / 브랜딩 영역)
  - Mobile: 단일 컬럼 구조  
    (스크롤 중심, 가독성 우선)

---

## 🧩 Page Structure

- Header  
  - 이름, 직종, 연락처 정보
- About Me  
  - 간단한 자기소개 및 프로필 이미지
- Education / Experience  
- Skills  
  - Skill bar 애니메이션으로 숙련도 표현
- Interest  

---

## ⚙️ Tech Stack

- HTML5  
- CSS3  
  - Grid / Flexbox
  - Media Query
- Git / GitHub

---

## 📱 Responsive Strategy

이 프로젝트에서 가장 중요하게 다룬 부분은 **반응형 레이아웃**입니다.

- PC  
  - Grid와 absolute를 활용한 디자인 중심 배치
- Mobile  
  - Flex 기반의 흐름 중심 레이아웃
  - absolute 해제 및 요소 재배치
  - 화면 크기에 따른 브레이크포인트 분기 (1280px / 768px / 420px / 380px)

> PC 디자인을 모바일에서 그대로 유지하기보다는,  
> 가독성과 안정성을 우선하는 방향으로 설계했습니다.

---

## 🚧 Challenges & Solutions

### 1. 모바일에서 레이아웃 깨짐 문제
-  가로선이 잘리거나 요소가 움직이지 않는 문제가 발생

**Solution**
- 모바일 구간에서 grid 해제
- 음수 margin 제거
- flex 기반 레이아웃으로 재구성

---

### 2. Contact 영역 반응형 이슈
- 380px 이하 화면에서 Contact 영역이 재배치되지 않음

**Solution**
- grid 구조를 flex column 구조로 전환
- 작은 화면에서 레이아웃을 단순화

---

## ✨ What I Learned

- 반응형 웹은 단순히 화면을 줄이는 작업이 아니라  
  **레이아웃 사고방식을 전환하는 과정**이라는 것을 배움
- 화면 크기에 따라 같은 화면이라도 다르게 정리하는 게 필요하다는 점
- CSS 구조를 설명할 수 있어야 좋은 코드라는 점

---

## 🔮 Future Improvements

- 모바일 화면을 기준으로 한 레이아웃 구조 개선
- 더 많은 사용자에게 읽기 편한 화면 구성
- 성능과 접근성 점검을 통한 품질 개선

---

## 🙌 Author

- Name: Park Sang Woo
- GitHub: https://github.com/swachieve-01
