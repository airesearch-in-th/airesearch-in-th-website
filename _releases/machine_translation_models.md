---
title: English-Thai Machine Translation Models
description: โมเดลแปลภาษา อังกฤษ-ไทย จากชุดข้อมูลกว่า 1 ล้าน คู่ประโยค
version: 1.0.0
items:
    -   item: SCB_1M+TBASE_en-th_moses-newmm_space_130000-130000_v1.0.tar.gz
        description: "Pre-trained en→th, word→word Transformer Base Model v1.0"
        size: 1.75G
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_moses-newmm_space_130000-130000_v1.0.tar.gz
        sha256: d2fb125ba0283e93c82416ec473e8308556ac4834bd1942a004a21ad8143b746
    
    -   item: SCB_1M+TBASE_en-th_moses-spm_130000-16000_v1.0.tar.gz
        description: "Pre-trained en→th, word→bpe Transformer Base Model v1.0"
        size: 1.09G
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_moses-spm_130000-16000_v1.0.tar.gz
        sha256: 4e8bb0a6323dc6c370d24f568775afa62011871467f474fbda03d4ac0b7681fa

    -   item: SCB_1M+TBASE_en-th_spm-newmm_space_16000-130000_v1.0.tar.gz
        description: "Pre-trained en→th, bpe→word Transformer Base Model v1.0"
        size: 1.22G
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_spm-newmm_space_16000-130000_v1.0.tar.gz
        sha256: 5ae3b712d97af0d1025e909866764772c44cb9f22435c1e91e5e7fb3e833d2c0

    -   item: SCB_1M+TBASE_en-th_spm-spm_32000-joined_v1.0.tar.gz
        description: "Pre-trained en→th, bpe→bpe Transformer Base Model v1.0"
        size: 667M
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_spm-spm_32000-joined_v1.0.tar.gz
        sha256: 016b9fb25f89c381271a098aeb04948bc4ed724cf211f061d561c3199f5f41c3

    -   item: SCB_1M+TBASE_th-en_newmm-moses_130000-130000_v1.0.tar.gz
        description: "Pre-trained th→en, word→word Transformer Base Model v1.0"
        size: 1.75G
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_newmm-moses_130000-130000_v1.0.tar.gz
        sha256: 7e255e2690964a6387909015682118d3afcccacfaf38e26eb5c6cd3b074c671b

    -   item: SCB_1M+TBASE_th-en_newmm-spm_130000-16000_v1.0.tar.gz
        description: "Pre-trained th→en, word→bpe Transformer Base Model v1.0"
        size: 1.1G
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_newmm-spm_130000-16000_v1.0.tar.gz
        sha256: 9d1d3d7e30c9cdb91823ec99125e2a2e1f58c1b9a3e84fca6e0abcfcb6f4cbd1

    -   item: SCB_1M+TBASE_th-en_spm-moses_16000-130000_v1.0.tar.gz
        description: "Pre-trained th→en, bpe→word Transformer Base Model v1.0"
        size: 1.21G
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_spm-moses_16000-130000_v1.0.tar.gz
        sha256: 92a68c4b4902d5fb1fba70f2849f09b0535a16a8f4a16277f8fb833d244989b8

    -   item: SCB_1M+TBASE_th-en_spm-spm_32000-joined_v1.0.tar.gz
        description: "Pre-trained th→en, bpe→bpe Transformer Base Model v1.0"
        size: 667M
        href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_spm-spm_32000-joined_v1.0.tar.gz
        sha256: 69bec33d471114ef51a0564a48b3c5c528e19544464361d62509531c5bfad153


order: 2
date: "22 June 2020"
featured: true
# image: '/assets/img/releases/test.jpg'
---


### Overview

<br/>

ศูนย์วิจัย AIResearch ซึ่งเกิดจากความร่วมมือระหว่าง VISTEC และ depa ได้ทำการเทรนโมเดลแปลภาษา (Machine Translation) สำหรับการแปลภาษาใน 2 คู่ภาษา ไทย→อังกฤษ และ อังกฤษ→ไทย จากชุดข้อมูลคู่ประโยคในภาษาอังกฤษ-ไทย (`scb-mt-en-th-2020`) ซึ่งมีจำนวนกว่า 1 ล้านคู่ประโยค และได้วัดประสิทธิภาพของโมเดลด้วย BLEU score กับข้อมูลชุดทดสอบจาก The International Conference on Spoken Language Translation (IWSLT) ในปี 2015 ซึ่งเป็น คู่ประโยค อังกฤษ-ไทย ที่ได้จากการถอดคำพูด (Transcription) จาก TED Talk จากผลการทดสอบพบว่า โมเดลแปลภาษาสำหรับ ภาษาไทย→อังกฤษ (`SCB_1M+TBASE-th-en_spm-spm_32000-joined_v1.0`) สามารถแปลภาษาได้มีประสิทธิภาพเทียบเท่าได้กับระบบแปลภาษาจาก Google Translation API (ทดสอบ ณ เดือนพฤษภาคม 2020) 

<br/>

### Transformer

<br/>

Transformer [Vaswani et al. 2017] เป็นโมเดลประเภท Sequence-to-Sequence ที่ออกแบบสำหรับการสร้างโมเดลแปลภาษา ซึ่ง Transformer นั้นถือว่า มีความแม่นยำสูงที่สุด ในปัจจุบัน (ปี 2020) อ้างอิงจากชุดข้อมูลทดสอบจาก จากงานประชุมทางวิชาการ Workshop on Statistical Machine Translation ปี 2013 (WMT2013) ในคู่ภาษา อังกฤษ→เยอรมัน 

<br/>
<center>
<img src='/assets/img/releases/machine_translation_models/eval_wmt2014_en_de.png' width="100%"/>
</center>

<br/>

<center>
รูป 1: การวัดผลโมเดลแปลภาษาใน Architecture ต่างๆ บนชุดข้อมูลทดสอบจากงานประชุมวิชาการ WMT ในปี 2013 สำหรับคู่ภาษา อังกฤษ→เยอรมัน (WMT2013 `en-de`) ในช่วงระหว่างปี 2016 - 2020 (ข้อมูลจาก paperwithcode.com) 
</center>

<br/>

สำหรับการเทรนโมเดลนั้น ทางทีมวิจัย ได้เทรนโมเดล Transformer แบบ Base ซึ่งมีจำนวนพารามิเตอร์ทั้งหมดกว่า 74 ล้านพารามิเตอร์ และใช้ Python library `fairseq` จาก Facebook AI Research โดยเทรนโมเดลบน NVIDIA DGX-1 ซึ่งเป็น Cluster ของ GPU NVIDIA V100

ชุดข้อมูลที่ใช้ในการเทรนโมเดลครั้งนี้มาจาก ชุดข้อมูลคู่ประโยคภาษาอังกฤษ-ไทย(`scb-mt-en-th-2020)` ซึ่งมีจำนวนกว่า 1 ล้านคู่ประโยค จากแหล่งที่มาต่างๆเช่น การจ้างนักแปลภาษา แปลบทสนทนาจากภาษาอังกฤษเป็นไทย และการ Crawl ข้อมูลจากเว็บไซต์ข่าวหรือองค์กร ที่มีเนื้อหาในทั้งสองภาษา โดยสามารถดูรายละเอียดเพิ่มเติมได้ที่ [English-Thai Machine Translation Dataset](https://airesearch.in.th/releases/machine-translation-datasets)
<br/>

### Evaluation results

<br/>

การเปรียบเทียบ BLEU score และ n-gram precision ระหว่าง ผลการแปลของโมเดลที่เทรนจาก ชุดข้อมูลคู่ประโยคภาษาอังกฤษ-ไทย `scb-mt-en-th-2020` (Our baseline) และ ผลการแปลจาก Google Translation API (ทดสอบและวัดผลใน เดือนพฤษภาคม 2020) โดยใช้ SacreBLEU [Post et al. 2018] (case sensitive / case-insentive) สำหรับภาษาอังกฤษเป็น Target language และ BLEU4 [Papineni et al. 2002] สำหรับภาษาไทยเป็น Target language


<center>
<img src='/assets/img/releases/machine_translation_models/eval_iwslt2015.png' width="100%"/>
</center>

<br/>

### Example 

<br/>

```
from fairseq.models.transformer import TransformerModel

MODEL_BASE_DIR = './SCB_1M+TBASE_th-en_spm-spm_32000-joined_v1.0/models/'
VOCAB_BASE_DIR = './SCB_1M+TBASE_th-en_spm-spm_32000-joined_v1.0/vocab/'
BPE_BASE_DIR = './SCB_1M+TBASE_th-en_spm-spm_32000-joined_v1.0/bpe/'

th2en = TransformerModel.from_pretrained(
            model_name_or_path=MODEL_BASE_DIR,
            checkpoint_file='checkpoint.pt',
            data_name_or_path=VOCAB_BASE_DIR,
            bpe='sentencepiece',
            sentencepiece_vocab=BPE_BASE_DIR + 'spm.th.model')

th2en.translate("งั้นเอาเป็นเวนติ แบล็คแอนด์ไวท์มอคค่าใส่นมสด 
               กับวิปครีม จากสตาร์บัคส์สาขาห้างเบิร์ชวิลล์นะคะ")
```

Translation:

```
so a venti black and white mocha with whole milk 
and whipped cream from the starbucks at the birchville mall.
```

<br/>

นอกจากนี้ทางศุนย์วิจัยได้เตรียม Jupyter Notebook สำหรับการทดสอบการรันโมเดล Machine Translation ได้โดยทันทีผ่าน [Google Colaboratory](https://colab.research.google.com/drive/1b7Uo9Ic1UltWvC2S7-qqix5WUL-P86xD?usp=sharing)

<br/>

### Versioning

<br/>

- Version 1.0 (23 June 2020)

    - โมเดล Pre-trained Transformer Base ที่เทรนจาก ชุดข้อมูลคู่ประโยคภาษาอังกฤษ-ไทย `scb-mt-en-th-2020` เวอร์ชั่น 1.0

<br/>

### References

<br/>

- Vaswani, Ashish & Shazeer, Noam & Parmar, Niki & Uszkoreit, Jakob & Jones, Llion & Gomez, Aidan & Kaiser, Lukasz & Polosukhin, Illia. (2017). Attention Is All You Need.

- Papineni, K., Roukos, S., Ward, T., & Zhu, W. J. (2002, July). BLEU: a method for automatic evaluation of machine translation. In Proceedings of the 40th annual meeting on association for computational linguistics (pp. 311-318). Association for Computational Linguistics.

- Post, Matt. (2018). A Call for Clarity in Reporting BLEU Scores.


