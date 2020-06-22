---
title: English-Thai Machine Translation Dataset
description: ชุดข้อมูลคู่ประโยคภาษาอังกฤษ-ไทย กว่า 1 ล้านคู่ประโยค
version: 1.0.0
items:
    -   item: scb-mt-en-th-2020.zip
        description: "scb-mt-en-th-2020 version 1.0"
        size: 144M
        href: https://github.com/vistec-AI/dataset-releases/releases/download/scb-mt-en-th-2020_v1.0/scb-mt-en-th-2020.zip
        sha256: 603e6256638db601763cff3291a296e4152fad6fddb4721031cce0f27925e7fe
    -   item: scb-mt-en-th-2020.tar.gz
        description: "scb-mt-en-th-2020 version 1.0 (tar.gz)"
        size: 144M
        href: https://github.com/vistec-AI/dataset-releases/releases/download/scb-mt-en-th-2020_v1.0/scb-mt-en-th-2020.tar.gz
        sha256: e9461b629ea88f5f02bf0c818404a3a45662ab04f4dfc3be913f39b951e011bb
order: 1
date: "22 June 2020"
featured: true
# image: '/assets/img/releases/test.jpg'

---

<br/>

### Overview

<br/>

ศูนย์วิจัย AIResearch ซึ่งเกิดจากความร่วมมือระหว่าง VISTEC และ depa ได้ทำการเผยแพร่ชุดข้อมูลคู่ประโยคในภาษาไทย-อังกฤษ จำนวนกว่า 1 ล้านคู่ประโยค โดยได้รับการสนับสนุนจาก SCB และเปิดข้อมูลสู่สาธารณะภายใต้ชื่อ `scb-mt-en-th-2020`  ชุดข้อมูลคู่ประโยคนี้ ได้รวบรวมจากหลายข้อมูลแหล่งอาทิเช่น ประโยคจากบทสนทนา  ข้อมูลจากเว็บไซต์ข่าวหรือองค์กรที่มีเนื้อหาในสองภาษา บทความวิกิพีเดีย และ เอกสารที่เผยแพร่จากทางการ 

การได้มาซึ่งคู่ภาษามีทั้ง การจ้างนักแปลภาษา และ การใช้ algorithm ในจับคู่ประโยคภาษาไทยและอังกฤษโดยอัตโนมัติ (Sentence alignemnt) จากหน้าเอกสาร บทความ และเว็บไซต์ 

โดยชุดข้อมูลนี้ เป็น model-ready หรือ พร้อมสำหรับการนำไปใช้ฝึกฝนโมเดลแปลภาษาได้ทันที ซึ่งทางศูนย์วิจัย ได้มี pre-trained model สำหรับการนำไปใช้งาน หรือ เอาไว้เป็น baseline model สามารถดูเพิ่มเติมที่ [Thai-English Machine Translation Model](https://www.airesearch.in.th/releases/machine-translation-models)

นอกจากนี้การสร้างชุดข้อมูล `scb-mt-en-th-2020` ยังทำให้ทางศูนย์ AIResearch ได้ชุดข้อมูลอื่นๆ ที่พร้อมจะนำไปแก้โจทย์ด้าน NLP อื่นๆ ดังนี้ 

1) คุณภาพการแปลประโยคจากอังกฤษเป็นภาษาไทย

2) การตัดแบ่งประโยคภาษาไทย

3) การ paraphrase ประโยคภาษาไทย

4) การคัดแยกคะแนนที่ได้รับจากรีวิวสินค้าในภาษาไทย

<br/>

### Dataset Statistics

<br/>

<img src="/assets/img/releases/machine_translation_datasets/scb-mt-en-th-2020_stats_v1.0.png" width="100%"/>
<center>ตาราง 1: จำนวนคู่ประโยคในภาษาอังกฤษ-ไทย แบ่งตาม แหล่งที่มาของข้อมูลและวิธีการจับคู่ประโยค รวมจำนวนคู่ประโยคทั้งหมดคือ 1,001,752 คู่ประโยค</center>
<br/>

### Source

<br/>

สำหรับแหล่งที่มาของชุดข้อมูลคู่ประโยค มีดังนี้

1. ชุดข้อมูลด้าน NLP จากต่างประเทศที่เผยแพร่สู่สาธารณะ โดยชุดข้อมูลที่นำมาใช้จะ ประกอบด้วย ชุดข้อมูลบทสนทนา (Taskmaster 1), ชุดข้อมูล SMS จากผู้ใช้ในสิงค์โปร์ (NUS SMS [Chen et al. 2013]) ชุดข้อมูลการ paraphrase ประโยค (Microsoft Research Paraphrase [Dolan et al. 2005]) แล้วชุดข้อมูลประโยคสำหรับโจทย์การ transcription จาก [Mozilla Common Voice](https://voice.mozilla.org/en)
2. การใช้โมเดล Text Generation เพื่อสร้างรีวิวสินค้าในภาษาอังกฤษ โดยทางศูนย์วิจัยได้ทำการสร้างรีวิวสินค้าในภาษาอังกฤษ จากโมเดล CTRL [Keskar et al. 2019] ซึ่งเป็นโมเดลสำหรับ การสร้างข้อความขึ้นมาใหม่ โดยสามารถกำหนดบริบทหรือรูปแบบของข้อความที่จะสร้างได้  
3. การเก็บข้อมูลจากหน้าเว็บไซต์ที่มีเนื้อหาในสองภาษา โดยอิงจากโดเมนภาษาไทยที่ถูกจัดอันใน alexa.com 500 อันดับแรก และโดเมนที่อยู่ในชุดข้อมูล Paracrawl Corpus [Esplà-Gomis et al. 2015] ซึ่งเป็นชุดข้อมูลที่รวบรวมเว็บไซต์ ที่มีเนื้อหาในภาษาอังกฤษ และภาษาในกลุ่มประเทศ  EU
4. เอกสารทางการที่มีเนื้อหาทั้งภาษาไทยและอังกฤษ อาทิเช่น แผนพัฒนาการเศรษฐกิจและสังคมแห่งชาติ ประมวลกฏหมายแพ่งและพาณิชย์
5. บทความจากวิกิพีเดียในภาษาไทยและภาษาอังกฤษ ที่มีเนื้อหาในหัวข้อเดียวกัน

<br/>

### Method

<br/>

1. การจ้างนักแปลภาษาโดยตรง 

    สำหรับการจ้างแปลโดยตรง จะเป็นการแปล จากชุดข้อมูล Taslmaster1 และ ชุดข้อมูลรีวิวสินค้าที่ถูกสร้างจาก โมเดล CTRL 

2. นักแปลจาก Crowdsourcing platform

    สำหรับการจ้างแปลจาก crowdsourcing platform จะเป็นการแปล จากชุดข้อมูล NUD SMS, Microsoft Research  Paraphrase, Mozilla common Voice และ ชุดข้อมูลรีวิวสินค้า

3. การจ้างนักแปลเพื่อทำการยืนยันความถูกต้องจากผลการแปล จาก Google Translation API 

    สำหรับวิธีนี้ ทางศูนย์วิจัยให้นำรีวิวสินค้า ส่วนหนึ่งจะส่งต่อไปยัง Google Translation API เพื่อทำการแปลเป็นภาษาไทยแล้วจึง ให้นักแปลยินยันความถูกต้องและความครบถ้วนของเนื้อหาจากผลการแปล

4. การใช้ algorithm ในการจับคู่ประโยคในภาษาไทย-อังกฤษ segment alignment จาก ข้อมูลที่ได้จากการ crawl wevsite บทความวิกิพีเดีย และ เอกสารทางการ 

    การจับคู่ประโยค ในส่วนของข้อมูลจากการ crawl และเอกสารจากทางการนั้น จะเป็นการจับคู่เอกสาร บทความ และ หน้าเว็บไซต์ก่อน (Document alignment / URL alginemnt ) แล้วจึงทำการจับคู่ประโยค (Sentence alignment)

<br/>

### Quality check

<br/>

สำหรับ การแปลจากการจ้างนักแปลโดยตรง จะมีทีมนักแปลที่ทำหน้าที่ตรวจสอบคุณภาพการแปล แต่ในส่วนของการ crawl ข้อมูลนั้น จะมีความผิดพลาดในการการจับคู่ประโยคสูง ทางศูนย์วิจัย ได้ใช้ โมเดล Universal Sentence Encoder Multilingual [Cer et al. 2018] ในการคำนวณหาการแปลที่ตรงกันระหว่างประโยคภาษาไทยและอังกฤษ และคัดกรองเอาคู่ประโยคไม่ได้จับคู่กันอย่างถูกต้องออก สำหรับวิธีการใช้ Universal Sentence Encoder Multilingual สามารถดูเพิ่มเติมได้จากบทความ [ตรวจสอบความถูกต้องของการแปล ด้วย Universal Sentence Encoder](https://medium.com/airesearch-in-th/%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B8%AA%E0%B8%AD%E0%B8%9A%E0%B8%84%E0%B8%A7%E0%B8%B2%E0%B8%A1%E0%B8%96%E0%B8%B9%E0%B8%81%E0%B8%95%E0%B9%89%E0%B8%AD%E0%B8%87%E0%B8%82%E0%B8%AD%E0%B8%87%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%81%E0%B8%9B%E0%B8%A5-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-universal-sentence-encoder-ad3c156c2e9b)

<br/>

### Versioning

<br/>

- Version 1.0: 23 June 2020
    - ชุดข้อมูลคู่ประโยคในภาษาไทย-อังกฤษ จำนวน1,001,752 คู่ประโนค

<br/>

### อ้างอิง

<br/>

- Tao Chen and Min-Yen Kan (2013). Creating a Live, Public Short Message Service Corpus: The NUS SMS Corpus. Language Resources and Evaluation, 47(2)(2013), pages 299-355.
- Dolan, W.B., & Brockett, C. (2005). Automatically Constructing a Corpus of Sentential Paraphrases. IWP@IJCNLP.
- Esplà-Gomis, M., Forcada, M.L., Ramírez-Sánchez, G., & Hoang, H. (2019). ParaCrawl: Web-scale parallel corpora for the languages of the EU. MTSummit.
- Keskar, N.S., McCann, B., Varshney, L.R., Xiong, C., & Socher, R. (2019). CTRL: A Conditional Transformer Language Model for Controllable Generation. ArXiv, abs/1909.05858.
- Cer, D.M., Yang, Y., Kong, S., Hua, N., Limtiaco, N., John, R.S., Constant, N., Guajardo-Cespedes, M., Yuan, S., Tar, C., Sung, Y., Strope, B., & Kurzweil, R. (2018). Universal Sentence Encoder. ArXiv, abs/1803.11175.

<br/>

#### Sponsored by



<img src="/assets/img/releases/logo/scb-bank.png" width="30%"/>