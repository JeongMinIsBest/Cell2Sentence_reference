# Cell2Sentence - Inference 실험 내역 💼

**Cell2Sentence 모델을 재학습하지 않고**, 이미 정의된 구조를 사용해 **F embedding을 추론(inference)** 하면서 출력 Representation의 특성을 관찰한 실험 기록을 답고 있습니다.
  
모든 실험은 Jupyter Notebook 기반으로 수행되었으며, 각 노트북은 이전 실험에서 생긴 의문을 다음 실험에서 확인하는 방식으로 진행되었습니다.
<br/>
<br/>

## 실험 구성 🧪

### 1. 초기 추론 실험  
**`initial_exp/cell2sentence_f_inference_exp1.ipynb`**
  
- Cell2Sentence inference 파이프라인이 실제로 동작하는지 확인
- 입력 데이터 형식과 출력 F embedding의 shape 확인
- embedding 값 범위 및 기본 분포 확인
  
→ 모델 구조 이해 및 sanity check 목적
<br/>
<br/>

### 2. 입력 변화에 따른 embedding 관찰  
**`analysis_exp/cell2sentence_f_inference_exp2.ipynb`**  
**`analysis_exp/cell2sentence_f_inference_exp3.ipynb`**
  
- 입력 cell 표현을 변경하면서 F embedding 변화 관찰
- 동일 구조, 다른 입력에 대한 embedding 차이 비교
- 단순 수치 비교 및 시각화를 통해 변화 패턴 확인
  
→ embedding이 입력 변화에 반응하는 방식 파악
<br/>
<br/>

### 3. embedding 안정성 및 분포 분석  
**`analysis_exp/cell2sentence_f_inference_exp4.ipynb`**  
**`analysis_exp/cell2sentence_f_inference_exp5.ipynb`**

- 반복 추론 시 embedding 분산 확인
- noise 또는 작은 입력 변화에 대한 민감도 관찰
- embedding 분포 형태 시각화

→ representation으로서의 안정성 확인
<br/>
<br/>

### 4. 분석 정리 및 활용 가능성 검토  
**`analysis_exp/cell2sentence_f_inference_exp6.ipynb`**  
**`analysis_exp/cell2sentence_f_inference_exp7.ipynb`**
  
- 이전 실험 결과 정리
- F embedding이 downstream 분석에 사용 가능한지 정성적으로 검토
- 실험 중 관찰된 특징 요약
  
→ “이 embedding을 써도 되는가?”에 대한 정리 단계
<br/>
<br/>

## 디렉토리 구조 🗂️
```
Cell2Sentence_reference-main/
├─ initial_exp/
│  └─ cell2sentence_f_inference_exp1.ipynb
│
└─ analysis_exp/
   ├─ cell2sentence_f_inference_exp2.ipynb
   ├─ cell2sentence_f_inference_exp3.ipynb
   ├─ cell2sentence_f_inference_exp4.ipynb
   ├─ cell2sentence_f_inference_exp5.ipynb
   ├─ cell2sentence_f_inference_exp6.ipynb
   └─ cell2sentence_f_inference_exp7.ipynb
```
<br/>
<br/>

## 참고 논문 🖋️
- [Cell2Sentence: Teaching Large Language Models the Language of Biology](https://www.biorxiv.org/content/10.1101/2023.09.11.557287v3)
<br/>
<br/>
