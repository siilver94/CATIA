# 📌 CATIA 파일 실행 및 설정 가이드 (INSTALL.md)  

이 문서는 **CATIA 파일(.CATPart, .CATProduct, .CATDrawing 등)을 실행하고 프로젝트 환경을 설정하는 방법**을 설명합니다.  
CATIA를 처음 사용하는 사용자도 따라 하기 쉽게 단계별로 정리하였습니다.  

---

## 🛠️ 1. CATIA 설치 방법  

### 1️⃣ CATIA 다운로드 및 설치  
CATIA는 다쏘 시스템즈(Dassault Systèmes)에서 제공하는 **유료 소프트웨어**이므로 정식 라이선스가 필요합니다.  
설치하려면 다음 단계를 따르세요:  

1. **[다쏘 시스템즈 공식 사이트](https://www.3ds.com/products-services/catia/)** 에서 라이선스를 확인하고 구매.  
2. 제공된 설치 파일을 다운로드한 후 실행.  
3. 설치 마법사의 안내에 따라 **CATIA 설치 경로 및 옵션 설정**.  
4. 설치 완료 후 라이선스를 활성화하고 실행.  

---

## 📂 2. 프로젝트 파일 구성  

CATIA 프로젝트는 여러 종류의 파일을 포함할 수 있습니다.  
파일을 이해하고 올바르게 실행하기 위해 아래 파일 구조를 참고하세요:  


📌 **파일 설명**  
- `.CATPart` : **부품(Part) 파일** – 개별적인 3D 모델을 저장.  
- `.CATProduct` : **어셈블리(Assembly) 파일** – 여러 개의 부품을 조립한 모델.  
- `.CATDrawing` : **도면(Drawing) 파일** – 2D 도면 및 제작용 설계도.  
- `.CATScript`, `.vbs` : **매크로 및 자동화 스크립트**.  

---

## 🚀 3. CATIA에서 파일 실행하는 방법  

### 1️⃣ 개별 부품 파일(.CATPart) 열기  
1. **CATIA 실행** → `File` → `Open` 선택.  
2. `models/` 폴더에서 `.CATPart` 파일을 선택하여 열기.  

### 2️⃣ 어셈블리 파일(.CATProduct) 실행  
1. `File` → `Open` 선택 후 `.CATProduct` 파일을 불러옴.  
2. 조립된 부품들이 화면에 표시되며, 개별 부품을 선택하여 편집 가능.  

### 3️⃣ 도면 파일(.CATDrawing) 실행  
1. `File` → `Open` → `drawing1.CATDrawing` 파일을 선택.  
2. 도면을 확인하고 **2D 뷰** 및 치수 측정을 수행.  

---

## 🔧 4. CATIA 기본 환경 설정  

### 1️⃣ 단위(Unit) 설정 변경  
- `Tools` → `Options` → `General` → `Parameters and Measure` → `Units`에서 **길이(mm), 무게(kg) 등 기본 단위 설정**.  

### 2️⃣ 성능 최적화  
- `Tools` → `Options` → `Display` → `Performance`에서 **렌더링 품질 및 성능 조정**.  
- `Graphics` 설정에서 **고성능 GPU 사용** 옵션 활성화.  

### 3️⃣ 파일 자동 저장 설정  
- `Tools` → `Options` → `General` → `Auto Save`에서 **자동 저장 간격 조정**(예: 5~10분).  

---

## 🖥️ 5. 권장 시스템 사양  

| 항목         | 최소 사양 | 권장 사양 |
|-------------|----------|----------|
| 운영체제(OS) | Windows 10 64-bit | Windows 11 64-bit |
| CPU         | Intel Core i5 | Intel Core i7 이상 |
| RAM         | 8GB | 16GB 이상 |
| GPU         | NVIDIA GTX 1050 | NVIDIA RTX 3060 이상 |
| 저장공간     | 50GB | 100GB 이상 (SSD 추천) |

---

## ❓ 6. 자주 묻는 질문 (FAQ)  

### 🔹 Q1. CATIA 실행 시 라이선스 오류가 발생합니다.  
✅ 해결 방법:  
1. `Start` → `Dassault Systemes` → `CATIA Licensing` 실행.  
2. 올바른 라이선스가 설정되었는지 확인 후 다시 실행.  

### 🔹 Q2. 어셈블리 파일을 열었는데 부품이 누락되었습니다.  
✅ 해결 방법:  
- `File` → `Desk`를 확인하여 누락된 `.CATPart` 경로를 수정하세요.  

### 🔹 Q3. CATIA에서 그래픽이 깨지거나 속도가 느립니다.  
✅ 해결 방법:  
- `Tools` → `Options` → `Display` → `Graphics` 설정을 조정하고 **고성능 GPU를 사용하도록 설정**.  

---

## 📚 7. 추가 참고 자료  

- [Dassault Systèmes 공식 홈페이지](https://www.3ds.com/products-services/catia/)  
- [CATIA 사용자 가이드](https://help.3ds.com/)  
- [CATIA 설치 및 설정 관련 FAQ](https://www.3ds.com/support/)  



