# AI for Digital Health — Labs (2026)

[![Leaderboard](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Leaderboard-yellow)](https://huggingface.co/spaces/wdittaya/aidh-leaderboard)

Hands-on labs for course **3099704 AI for Digital Health**, Master of Science Program in Digital Health, Faculty of Medicine, Chulalongkorn University.

Each lab is a self-contained Jupyter notebook that runs **free on Google Colab** with **public datasets** and **open-source models** only. All labs are **individual work**, done alongside the live Zoom sessions.

Lab notebooks are written in **Thai** (slides are in English).

> 🤖 **Note:** All labs in this repository (notebooks, synthetic data, and leaderboard code) were co-generated with [Claude](https://claude.ai) (Anthropic).

## สำหรับผู้เรียน: การเปิด การรัน และการส่งชิ้นงาน

ปฏิบัติการทุกครั้งเป็น **งานเดี่ยว** ซึ่งดำเนินการควบคู่กับการเรียนการสอนผ่าน Zoom โดยแต่ละปฏิบัติการประกอบด้วย 2 ส่วน ดังนี้

- ✅ **ส่วนหลัก — สำหรับผู้เรียนทุกคน ไม่จำเป็นต้องมีพื้นฐานการเขียนโปรแกรม** ให้รันเซลล์ตามลำดับจากบนลงล่าง เซลล์แบบฝึกหัด (ติดแท็ก **Exercise** และมีช่องว่าง `...` / `# TODO`) จะมีเซลล์ **✅ เฉลย** อยู่ถัดไปเสมอ ผู้เรียนควรทดลองทำแบบฝึกหัดด้วยตนเองก่อน หากไม่สามารถทำได้ ให้รันเซลล์เฉลยแล้วดำเนินการต่อ จากนั้นตอบคำถาม **✍️** ในเซลล์ข้อความ โน้ตบุ๊กที่รันครบทุกเซลล์พร้อมคำตอบถือเป็นชิ้นงานที่ต้องส่ง
- 🏆 **โจทย์ท้าทายบนตารางอันดับ (Leaderboard) — ไม่บังคับ สำหรับผู้เรียนที่เขียนโปรแกรมได้** ท้ายปฏิบัติการแต่ละครั้งมีโจทย์ซึ่งให้คะแนนโดยอัตโนมัติบน Hugging Face Space ของรายวิชา โดยเริ่มจากแบบจำลองพื้นฐาน (baseline) ที่รันได้ทันที การปรับปรุงผลลัพธ์เป็นกิจกรรมเสริม และไม่นับเป็นส่วนหนึ่งของชิ้นงานที่ต้องส่ง

ขั้นตอนการทำปฏิบัติการ

1. คลิกปุ่ม **Open in Colab** ของปฏิบัติการในตารางด้านล่าง แล้วเลือก `File → Save a copy in Drive` เพื่อบันทึกสำเนาของผู้เรียน
2. สำหรับปฏิบัติการที่ระบุว่าใช้ *GPU* ให้ตั้งค่า `Runtime → Change runtime type → T4 GPU` (ไม่มีค่าใช้จ่าย)
3. รันเซลล์ **⚙️ การตั้งค่า** ด้านบนของโน้ตบุ๊ก ทั้งนี้ `NAME` และ `JOIN_CODE` จำเป็นเฉพาะการเข้าร่วมโจทย์ท้าทายบนตารางอันดับ (ผู้สอนจะประกาศรหัสเข้าร่วมระหว่างการเรียนการสอนผ่าน Zoom และชื่อบนตารางอันดับจะแสดงแบบสาธารณะ จึงสามารถใช้นามแฝงได้)
4. ดำเนินการตามเซลล์ทีละขั้น ทำแบบฝึกหัด (หรือรันเซลล์เฉลย) และพิมพ์คำตอบในเซลล์ **✍️ คำตอบ** หากพบปัญหา สามารถสอบถามผู้สอนผ่านช่องแชตของ Zoom
5. *(ไม่บังคับ สำหรับผู้เรียนที่เขียนโปรแกรมได้)* ส่วนสุดท้ายของโน้ตบุ๊กจะสร้างไฟล์ผลการทำนายและเรียกใช้ `submit_to_leaderboard(...)` ซึ่งจะแสดงคะแนนและอันดับ
6. ส่งโน้ตบุ๊กที่ดำเนินการเสร็จสมบูรณ์ตามช่องทางที่รายวิชากำหนด


| # | Notebook | Topic | Dataset / Tools | GPU | 🏆 Leaderboard metric |
|---|----------|-------|-----------------|-----|-----------------------|
| 1 | [lab01](lab01_nocode_ai_and_data_exploration.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab01_nocode_ai_and_data_exploration.ipynb) | No-code AI + healthcare data exploration | Teachable Machine, Pima Diabetes, pandas | — | Balanced accuracy of a hand-written rule |
| 2 | [lab02](lab02_vibe_coding.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab02_vibe_coding.ipynb) | Vibe coding; auditing AI-generated code | AI coding assistant, scikit-learn | — | ROC AUC (Pima hold-out) |
| 3 | [lab03](lab03_supervised_unsupervised_rl.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab03_supervised_unsupervised_rl.ipynb) | Supervised / unsupervised / RL | UCI Heart Disease, scikit-learn, XGBoost | — | ROC AUC (heart hold-out) |
| 4 | [lab04](lab04_medical_image_classification.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab04_medical_image_classification.ipynb) | CNNs, transfer learning, labeling & segmentation | PneumoniaMNIST, PyTorch | ✅ | ROC AUC (624 test X-rays) |
| 5 | [lab05](lab05_object_detection_yolo.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab05_object_detection_yolo.ipynb) | Video processing & object detection | Ultralytics YOLO, brain-tumor MRI | ✅ | mAP@0.5 (223 val images) |
| 6 | [lab06](lab06_speech_processing.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab06_speech_processing.ipynb) | Speech processing / medical ASR | OpenAI Whisper (open weights), jiwer | ✅ | WER on 30 patient clips (lower is better) |
| 7 | [lab07](lab07_document_processing.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab07_document_processing.ipynb) | Document processing & clinical extraction | Tesseract OCR, regex, NER | — | F1 over extracted labs & medications (20 reports) |
| 8 | [lab08](lab08_llm_prompt_engineering.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab08_llm_prompt_engineering.ipynb) | LLMs & prompt engineering | Qwen2.5-1.5B-Instruct (open, Hugging Face) | ✅ | Extraction accuracy/F1 on 20 notes |
| 9 | [lab09](lab09_rag_and_agents.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab09_rag_and_agents.ipynb) | RAG & AI agents | sentence-transformers, FAISS, open LLM | ✅ | Recall@3 + abstention accuracy (22 questions) |
| 10 | [lab10](lab10_capstone_prototype.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wdittaya/AI-for-digital-health-course/blob/main/lab10_capstone_prototype.ipynb) | Capstone prototype workshop + common challenge | Diabetes 130-US hospitals, student choice | varies | ROC AUC, 30-day readmission (patient-level hold-out) |

## Leaderboard (optional)

Submit from your notebook with `submit_to_leaderboard(...)`, or upload a file in the **Submit** tab of the [leaderboard Space](https://huggingface.co/spaces/wdittaya/aidh-leaderboard). Test inputs are downloaded automatically by the notebooks.

- You need the **join code** announced in the live session. Leaderboard names are public — use a nickname if you prefer.
- The table shows each participant's best score; the *Overall* tab sums rank-based points across labs.
- Limits: 12 submissions per hour, 25 MB per file.
- **Honour code:** labels for labs 1–4 and 10 come from public datasets — do not look them up.

| Lab | Submission file | Metric |
|---|---|---|
| 1 | `id,prediction` CSV (0/1) for `pima/test_ids.csv` | balanced accuracy |
| 2, 3, 4, 10 | `id,prob` CSV | ROC AUC |
| 5 | JSON list `{image, class, conf, bbox:[x1,y1,x2,y2]}` on brain-tumor *val* | mAP@0.5 |
| 6 | `id,transcript` CSV for `asr/manifest.csv` | WER |
| 7 | JSON `{report_id: {labs:[{test,result,unit}], medications:[{name,dose_mg}]}}` | mean F1 |
| 8 | JSON `{note_id: {age, sex, conditions[], medications[]}}` | mean(acc, acc, F1, F1) |
| 9 | JSON `{question_id: {passages:[ids], answer}}` | 0.5·Recall@3 + 0.5·abstention |

## Course learning outcomes covered

- **CLO1** Principles of AI/ML/DL/GenAI and choosing approaches — Labs 1, 3, 4, 8
- **CLO2** Healthcare data exploration, cleaning, preprocessing, feature engineering — Labs 1, 2, 3, 7, 10
- **CLO3** Develop, evaluate, interpret ML/DL models with proper metrics — Labs 2, 3, 4, 5, 6, 10
- **CLO4** AI apps with ML/DL/LLM/RAG/agents — Labs 5, 6, 8, 9
- **CLO5** Evaluate AI technically, clinically, ethically — Labs 2, 4, 6, 8, 9
- **CLO6** Design an AI prototype for a real digital-health problem — Lab 10

## Datasets (all public)

- Pima Indians Diabetes — public domain
- UCI Heart Disease (Cleveland) and Diabetes 130-US Hospitals — UCI ML Repository (CC BY 4.0)
- MedMNIST (PneumoniaMNIST) — https://medmnist.com/ (CC BY 4.0)
- Brain-tumor detection — Ultralytics datasets (AGPL-3.0 code; dataset for research/education)
- Medical Speech, Transcription, and Intent — Paul Mooney, Kaggle (CC BY 4.0); 30 clips re-sampled to 16 kHz in `data/asr/`
- Lab reports (`data/ocr/`), clinical notes (`data/notes/`) and guideline passages (`data/rag/`) are **synthetic teaching material**, not clinical advice

> ⚠️ All clinical examples in the OCR / LLM / RAG labs are synthetic. Never paste real patient data into external models or services.

## License

Course materials for educational use. Datasets retain their own licenses.
