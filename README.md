# 복합대화 연구용 데이터셋 안내

이 저장소는 **복합대화 연구용 데이터셋을 찾기 위한 디렉터리**입니다. 데이터와 활용 코드는 아래 Hugging Face 저장소에서 확인할 수 있습니다. 데이터의 입력 형식, 이미지 준비 방법, 이용 조건은 각 데이터셋 카드에 정리되어 있습니다.

## 어떤 데이터를 사용할까요?

| 연구 목적 | 데이터셋 | 포함 내용 | 규모 |
| --- | --- | --- | --- |
| 이미지가 등장하는 **패션 상담 대화의 의도·상태·상호참조 분석** | [KoMMERCE: 패션 지식 대화](https://huggingface.co/datasets/KETI-NLP/multimodal_dialogue_coreference_resolution) | 한국어 패션 상담 대화, 이미지 URL, 발화별 의도·감정과 대화 상태·상호참조 주석 | 대화 15,293건 |
| 대화 중 **주제 전환과 긴 문맥 추적** | [Detour Dialogue](https://huggingface.co/datasets/KETI-NLP/detour-dialogue) | 여러 차례 주제가 바뀌는 한국어 다중 턴 대화. 일부 발화는 외부 사진을 참조 | 대화 19,449건 |
| 답변이 **실제 이미지 근거를 사용하는지** 학습 | [Image Grounding Preference](https://huggingface.co/datasets/KETI-NLP/image-grounding-preference) | WebQA 기반 한국어 질문에 대해 근거 사진이 있는 경우와 없는 경우의 선호·비선호 답변쌍 | 선호쌍 3,980건 |
| **한국 문화유산 사진 질의응답과 환각 완화** | [Korean Heritage VQA DPO](https://huggingface.co/datasets/KETI-NLP/korean-heritage-vqa-dpo-kogl1) | 국가유산포털의 공공누리 제1유형 원본 사진을 참조하는 질문, 선호·비선호 답변과 오답 이유 | 선호쌍 542,075건 |
| **이미지 속 한글 읽기(OCR)** 자료 구성 | [Korean OCR SFT Recipe](https://huggingface.co/datasets/KETI-NLP/korean-ocr-sft-recipe) | AI Hub 원천 이미지·라벨을 로컬에서 OCR 질문·답변과 학습용 JSONL로 변환하는 코드·안내 | **레시피만 제공**, 게시된 학습 레코드 0건 |

## 사용 전 확인

- 이미지가 필요한 자료도 대부분 사진 파일은 포함하지 않습니다. 각 Hugging Face 카드에 적힌 원천 제공처와 이미지 준비 절차를 확인해 주세요.
- OCR 저장소는 학습 데이터 다운로드용이 아닙니다. AI Hub 원천 **이미지와 라벨을 모두** 별도로 확보한 뒤 제공된 코드를 로컬에서 실행해야 합니다.
- 데이터별 이용 조건과 재배포 범위는 서로 다릅니다. 실제 사용 전 각 카드의 출처·이용 조건을 확인해 주세요.

수량은 **2026-11-20**에 각 Hugging Face 데이터셋 카드를 확인한 기준입니다.
