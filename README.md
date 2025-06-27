# 📘 AI 학습 정리

## 1. About GitHub, Markdown, Colab
- [GitHub 사용법](github-guide.md)
- [Markdown 문법](markdown-guide.md)  
- [Colab 기초](colab-guide.md)

## 2. About Python3
- [Python basic](./python3.md)
- https://www.w3schools.com/

---

## Markdown 문법
  - [Markdown 문법](#markdown-문법)  
---
## 🔰 1. 마크다운(Markdown)이란?

Markdown은 글을 **쉽게 꾸미기 위한 문법**이에요. HTML보다 간단하게 **제목, 목록, 굵은 글씨, 링크, 코드블록** 등을 작성할 수 있어요.
GitHub에서는 `README.md` 파일을 통해 마크다운을 많이 사용합니다.

---

## 🛠️ 2. GitHub에서 마크다운 사용하려면?

1. **GitHub 계정**을 만들고
2. 새 **Repository**를 만든 뒤
3. `README.md` 파일을 추가해서
4. 마크다운 문법을 사용하여 내용을 입력하면 됩니다.

---

## ✍️ 3. 기본 마크다운 문법 정리

| 기능        | 문법               | 예시                         | 결과                       |
| --------- | ---------------- | -------------------------- | ------------------------ |
| 제목(Title) | `#`, `##`, `###` | `## 내 프로젝트`                | 내 프로젝트                   |
| 굵게        | `**굵게**`         | `**중요**`                   | **중요**                   |
| 기울임       | `*기울임*`          | `*강조*`                     | *강조*                     |
| 목록        | `-`, `*`         | `- 사과` <br> `- 배`          | ● 사과 <br> ● 배            |
| 숫자 목록     | `1.`, `2.`       | `1. 첫째` <br> `2. 둘째`       | 1. 첫째 <br> 2. 둘째         |
| 링크        | `[이름](주소)`       | `[구글](https://google.com)` | [구글](https://google.com) |
| 이미지       | `![이름](이미지주소)`   | `![고양이](cat.jpg)`          | ![고양이](cat.jpg)          |
| 코드블록      | \`\`\`python     | `print("Hello")`           | 코드박스                     |
| 인라인 코드    | \`코드\`           | \`a = 3\`                  | `a = 3`                  |
| 구분선       | `---`            | `---`                      | ―――                      |

---
## 📷 4. 사진 넣는 방법
**복사 후 붙여넣기**

![귀여운고양이사진_(1)](https://github.com/user-attachments/assets/df528223-e781-4136-a7d4-5a1bdffcd99c)


---

## Colab 기초  
- [Colab 기초](#colab-기초)

**중요한 부분**
<img width="819" alt="스크린샷 2025-06-23 12 14 20" src="https://github.com/user-attachments/assets/a449c07d-ec6c-4de3-bf88-08b6950f0799" />


---

## 1. Colab이란?

- **무료**로 파이썬 코드를 작성하고 실행할 수 있는 웹 기반 도구
- **코드**와 **설명**을 섞어서 사용 가능

---

## 2. Colab 시작 방법

1. **구글에 "Colab" 검색** 후 접속
2. **NEW BOOK 만들기** 클릭
3. **코드 셀** 과 **텍스트 셀** 사용

---

## 3. Colab의 셀(Cell) 종류

| 셀 종류   | 설명                        | 사용 방법 예시                    |
| --------- | --------------------------- | ---------------------------------- |
| 코드 셀   | 파이썬 코드 입력 및 실행    | `print("안녕하세요!")`             |
| 텍스트 셀 | 마크다운으로 설명 작성 가능 | **굵게**, *기울임* 등 마크다운 사용 |

---

## 4. 마크다운 문법 요약 (Colab에서 사용)

| 기능           | 마크다운 문법 예시                | 결과 예시                  |
| -------------- | -------------------------------- | -------------------------- |
| 제목           | `# 제목1``## 제목2`          | # 제목1## 제목2        |
| 굵게           | `**굵게**` 또는 `__굵게__`       | **굵게**                   |
| 기울임         | `*기울임*` 또는 `_기울임_`       | *기울임*                   |
| 순서 없는 목록 | `- 사과``- 바나나`           | - 사과- 바나나         |
| 순서 있는 목록 | `1. 첫 번째``2. 두 번째`     | 1. 첫 번째2. 두 번째   |
| 인용문         | `> 인용문 예시입니다.`           | > 인용문 예시입니다.       |

---

## 5. Colab에서 마크다운 사용 방법

1. **셀 추가** 버튼 클릭
2. **텍스트 셀** 선택
3. 작성 후
4. **실행** 하면 보임

---

## 6. 파이썬 코드 실행 방법

1. **코드 셀** 선택
2. 파이썬 코드 입력 
3. **실행** 하면 결과가 아래에 나옴

--- 
## 3.  data structure / data sciencs

- [데이터 구조 개요](./data_structures.md)
- [Pandas](./pandas.md)
- [Numpy](./numpy.md)
- [Matplotlib](./Matplotlib.md)

## 4. Machine Learning

- [Machine Learning Basic](./ml_basic.md)
- [모델 훈련 및 평가](./ml_test.md)

## 5. OpenCV

- [OpenCV Basic](./OpenCV_basic.md)
- [이미지 처리](./image_test.md)

  
## 6. CNN(Convolution Neural Network
- [CNN_Basic](./CNN_basic.md)
- [CNN_자율주행 관련 코드](./cnn_test.md)

## 7. Ultralytics
- [Ultralytics_Basic](./Ultralytics_basic.md)
- [YOLOv8](./YOLOv8_test.md)
- [YOLOv12](./YOLOv12_test.md)
  
## 8. TensorRT vs PyTorch 
- [PyTorch_Basic](./PyTorch_basic.md)
- [TensorRT](./TensorRT_test.md)
- [YOLOv12](./YOLOv12_test.md)

## 9. TAO Toolkit on RunPod
- [TAO_사용법](.TAO_install.md)
- [TAO_Toolkit](.TAO_Toolkit.md)

## 10. 칼만필터, CARLA, 경로 알고리즘
- [kalman](.kalman.md)
- [CARLA_simulator](.CARLA.md)

## 11. ADAS & (ADAS TensorRT vs PyTorch)
- [adas_basic](.adas_basic.md)
- [TensorRT vs PyTorch 비교](.vs.md)
- 
