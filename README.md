# 🌟 디지털 칭찬 상자+

> 학생 이름과 칭찬 문구를 랜덤으로 추첨해주는 Streamlit 앱  
> - 학생 중복 등장 방지  
> - 한국시간(KST) 기록 저장  
> - 레트로 CRT 화면 스타일  
> - 랜덤 사운드 효과 지원  

---

## 🚀 주요 기능
- **학생 이름 + 칭찬 문구 랜덤 추첨**
- 한 번 뽑힌 학생은 중복되지 않음
- 추첨 시 랜덤 사운드 효과(mp3) 재생
- 모든 기록 CSV 다운로드 가능
- 완전한 레트로 CRT 화면 스타일
- 한국 시간 기준 추첨 시각 기록
- 학생/문구 목록을 직접 추가·저장 가능

---

## 📂 폴더 구조
```

project/
│
├── streamlit\_app.py         # 앱 메인 코드
├── requirements.txt         # 의존성 목록
├── README.md                # 프로젝트 설명 파일
└── assets/                  # 효과음 mp3 저장 폴더
├── success1.mp3
├── coin.mp3
└── win.mp3

````

---

## 🛠 설치 및 실행
### 1. 저장소 클론
```bash
git clone https://github.com/username/digital-praise-box.git
cd digital-praise-box
````

### 2. 의존성 설치

```bash
pip install -r requirements.txt
```

### 3. 실행

```bash
streamlit run streamlit_app.py
```

---

## 🎵 효과음 추가 방법

* `assets/` 폴더에 mp3 파일을 넣으면 랜덤으로 재생됩니다.
* 예시:

  * `success1.mp3`
  * `coin.mp3`
  * `win.mp3`

---

## 📝 사용 예시

1. **학생명단 입력** → 저장
2. **칭찬 문구 입력** → 저장
3. **오늘의 칭찬 주인공 뽑기** 버튼 클릭
4. 레트로 CRT 화면에 결과 표시 + 효과음 재생
5. 기록 확인 및 CSV 다운로드 가능

---

## 📜 라이선스

© 2025 이대형. All rights reserved.
[https://aicreatorz.netlify.app/](https://aicreatorz.netlify.app/)