## Mahdi Bedja

AI engineer based in Paris. I graduated from ESI Algiers (engineering degree in computer science) and I'm currently doing a Master 2 in Intelligent Systems at Sorbonne Paris Nord. I'm looking for a final-year internship (PFE) in applied AI starting March 2027.

Portfolio: [mehdibedja.github.io](https://mehdibedja.github.io) · [LinkedIn](https://www.linkedin.com/in/mahdi-bedja-0b94031b3/) · mahdibedja@gmail.com

### Work

**AI Engineer, BM TECH** (Algiers, Nov 2025 – Aug 2026)

BM TECH makes software for medical laboratories and hospitals. The code below belongs to the company, so it isn't on this profile, but this is what I worked on:

- Detection, segmentation and classification of 14 lung pathologies on chest X-rays (YOLO, CNNs), and a separate bone fracture detection pipeline.
- French medical speech recognition: I built a synthetic dataset by cloning physicians' voices with Qwen3 from real radiology reports, then fine-tuned Whisper. 3% WER on a held-out synthetic test set.
- Real-time medical dictation on top of WhisperLiveKit / faster-whisper, with fuzzy matching and voice commands. 8% WER in live streaming.
- An agentic RAG system (LangChain, locally hosted Qwen models) for answering questions over patient records and clinical documents.
- Semantic matching of lab test results across hospitals using dense embeddings of the LOINC dataset.
- Packaging the services with Docker, with structured logging and monitoring.

**Engineering intern, CM Consulting** (Algiers, summer 2024): a Python tool that extracts and structures data from PDF tenders (spaCy, pdfplumber) and generates formatted reports.

### Projects

**Mobile pest detection (engineering thesis).** I benchmarked YOLOv7 to v11, SSD and Faster R-CNN on a curated 13-class subset of IP102, picked YOLOv11s (93.8% mAP@50), and shipped it as a TFLite model inside an Android app that works offline. The app syncs with a Django backend.

- [pest-detection-system](https://github.com/MehdiBedja/pest-detection-system): overview
- [pest-detection-computer-vision](https://github.com/MehdiBedja/pest-detection-computer-vision): dataset work, training and benchmark results
- [pest-detection-android](https://github.com/MehdiBedja/pest-detection-android): Kotlin / Jetpack Compose app
- [pest-detection-api](https://github.com/MehdiBedja/pest-detection-api): Django REST backend

Smaller projects:

- [event-ticketing-postgres](https://github.com/MehdiBedja/event-ticketing-postgres): PostgreSQL schema and PL/pgSQL functions, Flyway migrations, Jenkins pipeline
- [parking-reservation-api](https://github.com/MehdiBedja/parking-reservation-api) and [parking-reservation-android](https://github.com/MehdiBedja/parking-reservation-android): parking reservation app
- [docx-certificate-generator](https://github.com/MehdiBedja/docx-certificate-generator): generates Word certificates from a list
- [ml-zoomcamp](https://github.com/MehdiBedja/ml-zoomcamp): ML Zoomcamp coursework

### Skills

Python, PyTorch, TensorFlow, Hugging Face, LangChain, Whisper, YOLO, TFLite, Django, PostgreSQL, Kotlin, Docker.

English (C1, IELTS 7.5), French (C1, TCF), Arabic (native).
