# GraphRAG를 활용한 EpubReader
<!--![image]()-->

#### 🎓 SW 산학협력 프로젝트 🎓
> 본 프로젝트는 **SW 산학협력 프로젝트**로, **과학기술정보통신부 주관** 아래 진행되었습니다.  
- **프로젝트 기간:** 2024.09.13 ~ 2025.02.07  

## 👋 프로젝트에 오신 것을 환영합니다 👋

**Graph-EpubReader**는 EPUB 전자책을 시각적으로 탐색하고 읽을 수 있는 혁신적인 리더 애플리케이션입니다. 그래프 기반의 인터페이스를 통해 사용자는 책의 구조를 직관적으로 파악하고, 원하는 챕터나 섹션으로 쉽게 이동할 수 있습니다.

이 프로젝트는 **Microsoft**의 **GraphRAG 기술을 활용한 최초의 파일럿 프로젝트**로, 기업이 향후 **GraphRAG**를 활용하여 데이터를 보다 효율적으로 관리하고 **검색 및 추론**할 수 있는 방향성을 제시하는 데 중요한 역할을 합니다.


<p align="center">
    <img src="https://img.shields.io/github/stars/GolddBunny/Graph-EpubReader" alt="GitHub stars">
    <img src="https://img.shields.io/github/license/GolddBunny/Graph-EpubReader" alt="GitHub license">
</p>

---

## 🏆 프로젝트 수상 내역 🏆

Graph-EpubReader는 아래와 같은 대회에서 수상한 바 있습니다.


- **제11회 한성대학교 C&C Festival(창의융합성과 경진대회)** - 대상
- **2024 SW중심대학 연합 SW FESTIVAL (빅데이터/인공지능 부문)** - 빅데이터 및 AI 부문 3위(장려상)


이러한 수상 경력은 프로젝트의 혁신성과 실용성을 인정받은 결과이며, 지속적인 개선과 발전을 위한 원동력이 되고 있습니다.


| 2024 SW중심대학 연합 SW FESTIVAL 대회<br> (빅데이터/인공지능 부문 장려상, 3위)  | 제11회 한성대학교 C&C Festival(창의융합성과 경진대회)<br> 대상(1위) |
|---|---|
| ![image](https://github.com/user-attachments/assets/05fc0b1a-2bdc-42ad-85bb-fb8f32fc7379)
  |   |


---

## ✨ 주요 기능 ✨

- **그래프 기반 책 탐색**: 책의 목차를 그래프로 시각화하여 사용자가 전체 구조를 쉽게 파악하고 원하는 부분으로 빠르게 이동할 수 있습니다.

- **EPUB 파일 지원**: EPUB 형식의 전자책을 완벽하게 지원하여 다양한 서적을 열람할 수 있습니다.

- **GraphRAG 기반 지식 그래프 탐색**: 
  - 전자책의 내용을 분석하여 등장인물, 장소, 사건 등의 엔터티와 그 관계를 **지식 그래프**로 시각화합니다.
  - 책의 내용을 효율적으로 검색하고, 특정 개념이나 관계를 직관적으로 탐색할 수 있습니다.
  - 사용자가 특정 키워드를 입력하면, GraphRAG를 활용해 관련 정보 및 연관된 내용을 추천합니다.

- **사용자 친화적인 인터페이스**: 직관적이고 깔끔한 UI를 통해 누구나 쉽게 사용할 수 있습니다.


## 📚 기술 스택 📚

- **React**: 사용자 인터페이스를 구축하기 위한 JavaScript 라이브러리입니다.
- **D3.js**: 데이터 시각화를 위한 강력한 라이브러리로, 그래프 탐색 기능을 구현하는 데 사용되었습니다.
- **Node.js**: 백엔드 서버 구축을 위한 JavaScript 런타임입니다.
- **Microsoft GraphRAG**: 대규모 언어 모델(LLM)과 지식 그래프를 결합하여 복잡한 정보 검색을 최적화하는 기술입니다.


## 📂 프로젝트 구조 📂

- **public/**: 공용 파일 및 정적 자원이 위치한 디렉토리입니다.
- **src/**: 소스 코드가 위치한 디렉토리로, 주요 컴포넌트와 로직이 포함되어 있습니다.
  - **components/**: 재사용 가능한 React 컴포넌트들이 위치합니다.
  - **pages/**: 애플리케이션의 주요 페이지 컴포넌트들이 위치합니다.
  - **utils/**: 유틸리티 함수들이 위치합니다.
- **package.json**: 프로젝트의 메타데이터와 의존성 정보가 포함되어 있습니다.


## 📽️ 데모 영상

[![GraphRAG EPUB Reader Demo](https://github.com/user-attachments/assets/0ba36c65-c204-41c0-846e-bad8313f33ab)](https://youtu.be/RPfeBtiNFm4)

---

## 🚀 시작하기 🚀

1. **레포지토리 클론하기:**  
   `git clone https://github.com/GolddBunny/Graph-EpubReader.git`

2. **프로젝트 디렉토리로 이동:**  
   `cd Graph-EpubReader`

3. **의존성 설치:**  
   `npm install`

4. **애플리케이션 실행:**  
   `npm start`
   - 브라우저에서 `http://localhost:3000`을 열어 애플리케이션을 확인할 수 있습니다.

---

## 🔗 Microsoft GraphRAG 통합 🔗

Graph-EpubReader는 **Microsoft의 GraphRAG를 활용한 파일럿 프로젝트**로, 대규모 언어 모델(LLM)을 사용하여 전자책의 데이터를 효과적으로 검색하고, 지식 그래프를 활용한 분석을 제공합니다.

**GraphRAG를 활용한 주요 기능:**

- **전자책 내용 자동 요약**:

  - 챕터별 주요 내용을 자동 요약하여 사용자가 빠르게 개요를 파악할 수 있습니다.

- **지식 그래프 기반 검색**:

  - 등장인물, 장소, 사건 등의 정보를 지식 그래프로 시각화하여 직관적인 탐색이 가능합니다.

- **질문 응답 시스템 강화**:

  - 사용자가 특정 내용을 질문하면 GraphRAG가 전자책에서 관련 정보를 찾아 제공하는 **AI 기반 검색 기능**을 제공합니다.

**GraphRAG 통합 방법:**

1. **GraphRAG 설치**:

   ```bash
   pip install graphrag
   ```

2. **전자책 내용 분석 및 지식 그래프 생성**:
- EPUB 파일의 텍스트를 분석하여 **엔터티와 관계**를 추출하고, 이를 기반으로 **지식 그래프를 생성**합니다.

3. **Graph-EpubReader와의 통합**:
- 생성된 지식 그래프 데이터를 React 및 D3.js를 활용하여 시각화하고, 사용자 인터페이스와 상호작용을 구현합니다.

---

## 📌 기업을 위한 GraphRAG 활용 방향
Graph-EpubReader는 **GraphRAG를 활용한 최초의 파일럿 프로젝트**로서, 기업이 이 기술을 도입하여 데이터 검색 및 활용 방식을 혁신할 수 있는 방향성을 제시합니다.

1. **문서 및 데이터 검색 최적화**:

- 기존의 키워드 기반 검색을 넘어, 문서 내의 관계형 데이터를 활용하여 보다 정확하고 맥락적인 검색 결과를 제공할 수 있습니다.

2. **AI 기반 정보 분석 및 요약**:

- 기업 문서, 연구 자료, 매뉴얼 등을 GraphRAG로 분석하여 자동으로 요약 및 연관 정보를 추출할 수 있습니다.

3. 지식 그래프를 활용한 데이터 탐색:

- 문서 내 인사이트를 직관적으로 분석할 수 있도록, 데이터의 관계를 시각화하여 새로운 가치를 창출할 수 있습니다.

4. **고객 지원 및 Q&A 시스템 강화**:

- 고객이 질문을 하면, 기존 FAQ나 문서에서 관련 정보를 **AI 기반으로 제공하는 지능형 챗봇 시스템**을 구축할 수 있습니다.

---

## 📄 관련 논문 📄

본 프로젝트와 관련된 연구 및 논문을 아래에서 확인할 수 있습니다.

- **EPUB 리더기의 GraphRAG 활용에 관한 연구** - 박채원,옥지윤,한지운,성주연,황기태, 2024, [링크](https://github.com/user-attachments/files/17943916/EPUB.GraphRAG.pdf)

- **GraphRAG를 활용하여 뛰어난 검색과 추론 기능을 가진 EPUB 리더** - 박채원,옥지윤,한지운,성주연,황기태, 2024, [링크](https://github.com/user-attachments/files/18278657/GraphRAG.EPUB.pdf)


## 📄 관련 문서 📄

- [2024 SW중심대학 연합 SW FESTIVAL (빅데이터/인공지능 부문) 제출PDF](https://github.com/user-attachments/files/18728207/2024.SW._.pdf)

---

✨ **Special Thanks** ✨  
이 프로젝트는 오픈 소스 커뮤니티와 [Microsoft의 GraphRAG](https://github.com/microsoft/graphrag) 연구진의 지원을 바탕으로 탄생했습니다. 
특히, D3.js 및 GraphRAG 같은 강력한 도구를 제공해 주신 개발자분들께 감사드립니다. 🚀  

자세한 내용은 [GitHub 리포지토리](https://github.com/GolddBunny/Graph-EpubReader)를 확인해 주세요.
