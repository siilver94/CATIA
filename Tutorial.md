# 📌 CATIA 기본 사용법 및 모델링 튜토리얼  

이 문서는 CATIA를 처음 사용하는 사용자를 위해 **기본적인 조작법과 3D 모델링 방법**을 설명합니다.  
이 가이드를 따라 하면 **단순한 3D 부품 설계부터 어셈블리 조립, 도면 작성까지** 경험할 수 있습니다.  

---

## 🛠️ 1. CATIA 기본 인터페이스  

### 🔹 시작 화면 (Welcome Page)  
CATIA 실행 후 다음과 같은 주요 기능을 확인할 수 있습니다:  
- **Start**: 새로운 프로젝트를 생성  
- **File** → **Open**: 기존 CATIA 파일(.CATPart, .CATProduct, .CATDrawing) 열기  
- **Workbench 선택**: 설계 유형에 따라 적절한 작업 환경을 설정  

📌 **Workbench란?**  
CATIA에서는 작업 유형에 따라 워크벤치를 선택해야 합니다.  
| 워크벤치 이름 | 기능 |
|-------------|------------------------------------------------|
| Part Design | 개별 부품(Part) 모델링 |
| Assembly Design | 여러 부품을 조립하여 어셈블리 생성 |
| Drafting | 2D 도면 생성 |
| Generative Shape Design | 곡면(Surface) 모델링 |
| Sheet Metal Design | 판금 부품 설계 |

---

## 🏗️ 2. 기본 3D 모델링 (Part Design)  

### 1️⃣ 새로운 부품 생성  
1. **File** → **New** → `Part` 선택 후 `OK` 클릭.  
2. 좌측 `Tree` 패널에서 `Part1` 확인.  

### 2️⃣ 스케치 그리기  
1. **Sketcher Workbench**(스케치 작업 공간) 진입:  
   - `XY Plane`을 선택 후 `Sketch` 버튼 클릭.  
2. **기본 형상 그리기**:  
   - 직사각형, 원, 다각형 등을 `Profile` 도구를 이용해 그림.  
   - `Constraint`(구속 조건)으로 크기 및 정렬을 설정.  

### 3️⃣ 3D 모델 생성  
1. **Pad (돌출)**: 스케치를 선택하고 `Pad` 버튼을 눌러 3D 형상 생성.  
2. **Pocket (컷팅)**: 선택한 스케치를 이용해 형상을 절삭.  
3. **Fillet (모서리 둥글리기)**: 특정 엣지를 선택 후 곡률 반경 적용.  
4. **Chamfer (모서리 깎기)**: 모서리를 경사지게 가공.  

---

## 🔗 3. 어셈블리 조립 (Assembly Design)  

### 1️⃣ 새로운 어셈블리 생성  
1. **File** → **New** → `Product` 선택 후 `OK` 클릭.  
2. `Existing Component`를 선택하여 기존 `.CATPart` 불러오기.  

### 2️⃣ 부품 배치 및 조립  
1. **Constraints (구속 조건)** 설정:  
   - **Coincidence** (일치): 두 면을 맞춤  
   - **Contact** (접촉): 특정 면을 접촉  
   - **Fix** (고정): 특정 부품을 고정  
2. `Update` 버튼을 눌러 조립이 올바르게 되었는지 확인.  

---

## 📐 4. 2D 도면 작성 (Drafting)  

### 1️⃣ 도면 생성  
1. **File** → **New** → `Drawing` 선택 후 `OK`.  
2. `Front View` 또는 `Isometric View`를 추가하여 부품 투상.  

### 2️⃣ 치수 및 주석 추가  
1. `Dimension` 도구를 사용하여 길이, 반지름, 각도 표시.  
2. `Text` 도구를 이용해 설명 추가.  

### 3️⃣ 도면 저장 및 출력  
- `File` → `Save As` → `.CATDrawing` 또는 `.PDF`로 저장.  

---

## ⌨️ 5. 유용한 단축키  

| 단축키 | 기능 |
|-------|-------------------------------|
| **Ctrl + N** | 새 파일 생성 |
| **Ctrl + O** | 파일 열기 |
| **Ctrl + S** | 파일 저장 |
| **F3** | 트리(Tree) 표시/숨김 |
| **F8** | 스케치 모드(Sketcher) 진입 |
| **V, H** | 수직/수평 정렬 |
| **M** | 미러(Mirror) 기능 |

---

## 🎯 6. 추가 팁 및 주의 사항  

### ✅ 모델링 팁  
✔ 항상 `Constraints`(구속 조건)를 활용하여 정확한 설계를 유지하세요.  
✔ 곡면 모델링(Surface Modeling)이 필요할 경우 **Generative Shape Design** 워크벤치를 사용하세요.  

### ⚠️ 주의 사항  
- 모델링 중 **Undo(되돌리기)**가 제한적일 수 있으므로 `Save As`를 활용하여 중간 저장하세요.  
- 어셈블리 설계 시 경로 설정을 정확히 해두지 않으면 부품 파일을 찾지 못할 수 있습니다.  

---

## 📚 7. 참고 자료  

- [Dassault Systèmes 공식 CATIA 문서](https://www.3ds.com/products-services/catia/)  
- [CATIA 튜토리얼 영상](https://www.youtube.com/results?search_query=CATIA+Tutorial)  
- [CATIA 커뮤니티 포럼](https://www.eng-tips.com/threadcategory.cfm?lev2=77)  

