---
title: English-Thai Machine Translation Models
description: โมเดลแปลภาษา อังกฤษ-ไทย จากชุดข้อมูลกว่า 1 ล้าน คู่ประโยค
version: 1.0
items:
  - item: SCB_1M+TBASE_en-th_moses-newmm_space_130000-130000_v1.0.tar.gz
    description: "Pre-trained en→th, word→word Transformer Base Model v1.0 (SCB_1M)"
    size: 1.75G
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_moses-newmm_space_130000-130000_v1.0.tar.gz
    sha256: d2fb125ba0283e93c82416ec473e8308556ac4834bd1942a004a21ad8143b746
  - item: SCB_1M+TBASE_en-th_moses-spm_130000-16000_v1.0.tar.gz
    description: "Pre-trained en→th, word→bpe Transformer Base Model v1.0 (SCB_1M)"
    size: 1.09G
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_moses-spm_130000-16000_v1.0.tar.gz
    sha256: 4e8bb0a6323dc6c370d24f568775afa62011871467f474fbda03d4ac0b7681fa
  - item: SCB_1M+TBASE_en-th_spm-newmm_space_16000-130000_v1.0.tar.gz
    description: "Pre-trained en→th, bpe→word Transformer Base Model v1.0 (SCB_1M)"
    size: 1.22G
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_spm-newmm_space_16000-130000_v1.0.tar.gz
    sha256: 5ae3b712d97af0d1025e909866764772c44cb9f22435c1e91e5e7fb3e833d2c0
  - item: SCB_1M+TBASE_en-th_spm-spm_32000-joined_v1.0.tar.gz
    description: "Pre-trained en→th, bpe→bpe Transformer Base Model v1.0 (SCB_1M)"
    size: 667M
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_en-th_spm-spm_32000-joined_v1.0.tar.gz
    sha256: 016b9fb25f89c381271a098aeb04948bc4ed724cf211f061d561c3199f5f41c3
  - item: SCB_1M+TBASE_th-en_newmm-moses_130000-130000_v1.0.tar.gz
    description: "Pre-trained th→en, word→word Transformer Base Model v1.0 (SCB_1M)"
    size: 1.75G
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_newmm-moses_130000-130000_v1.0.tar.gz
    sha256: 7e255e2690964a6387909015682118d3afcccacfaf38e26eb5c6cd3b074c671b
  - item: SCB_1M+TBASE_th-en_newmm-spm_130000-16000_v1.0.tar.gz
    description: "Pre-trained th→en, word→bpe Transformer Base Model v1.0 (SCB_1M)"
    size: 1.1G
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_newmm-spm_130000-16000_v1.0.tar.gz
    sha256: 9d1d3d7e30c9cdb91823ec99125e2a2e1f58c1b9a3e84fca6e0abcfcb6f4cbd1
  - item: SCB_1M+TBASE_th-en_spm-moses_16000-130000_v1.0.tar.gz
    description: "Pre-trained th→en, bpe→word Transformer Base Model v1.0 (SCB_1M)"
    size: 1.21G
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_spm-moses_16000-130000_v1.0.tar.gz
    sha256: 92a68c4b4902d5fb1fba70f2849f09b0535a16a8f4a16277f8fb833d244989b8
  - item: SCB_1M+TBASE_th-en_spm-spm_32000-joined_v1.0.tar.gz
    description: "Pre-trained th→en, bpe→bpe Transformer Base Model v1.0 (SCB_1M)"
    size: 667M
    href: https://github.com/vistec-AI/model-releases/releases/download/SCB_1M%2BTBASE_v1.0/SCB_1M+TBASE_th-en_spm-spm_32000-joined_v1.0.tar.gz
    sha256: 69bec33d471114ef51a0564a48b3c5c528e19544464361d62509531c5bfad153

date: "23 June 2020"
featured: true
categories: model demo
image: "/assets/img/releases/letters.jpg"
---

สถาบันวิจัยปัญญาประดิษฐ์ประเทศไทย ได้ทำการเทรนโมเดลแปลภาษา (Machine Translation) สำหรับการแปลภาษาใน 2 คู่ภาษา ไทย→อังกฤษ และ อังกฤษ→ไทย จากชุดข้อมูลคู่ประโยคในภาษาอังกฤษ-ไทย (scb-mt-en-th-2020) ซึ่งมีจำนวนกว่า 1 ล้านคู่ประโยค และได้วัดประสิทธิภาพของโมเดลด้วย BLEU score กับข้อมูลชุดทดสอบจาก The International Conference on Spoken Language Translation (IWSLT) ในปี 2015 ซึ่งเป็น คู่ประโยค อังกฤษ-ไทย ที่ได้จากการถอดคำพูด (Transcription) จาก TED Talk จากผลการทดสอบพบว่า โมเดลแปลภาษาสำหรับ ภาษาไทย→อังกฤษ (`SCB_1M-MT_OPUS+TBASE`) และ ภาษาอังกฤษ→ไทย (`SCB_1M-MT_OPUS+TBASE`) สามารถแปลภาษาได้มีประสิทธิภาพเทียบเท่าหรือดีกว่าระบบแปลภาษาจาก Google Translation API (ทดสอบ ณ เดือนพฤษภาคม 2020)

## Transformer

Transformer [Vaswani et al. 2017] เป็นโมเดลประเภท Sequence-to-Sequence ที่ออกแบบสำหรับการสร้างโมเดลแปลภาษา ซึ่ง Transformer นั้นถือว่า มีความแม่นยำสูงที่สุด ในปัจจุบัน (ปี 2020) อ้างอิงจากชุดข้อมูลทดสอบจาก จากงานประชุมทางวิชาการ Workshop on Statistical Machine Translation ปี 2013 (WMT2013) ในคู่ภาษา อังกฤษ→เยอรมัน

![Transformer Evaluation](/assets/img/releases/machine_translation_models/eval_wmt2014_en_de.png)

<p style="text-align: center;">รูป 1: การวัดผลโมเดลแปลภาษาใน Architecture ต่างๆ บนชุดข้อมูลทดสอบจากงานประชุมวิชาการ WMT ในปี 2013 สำหรับคู่ภาษา อังกฤษ→เยอรมัน (WMT2013 en-de) ในช่วงระหว่างปี 2016 - 2020 (ข้อมูลจาก paperwithcode.com)</p>

สำหรับการเทรนโมเดลนั้น ทางทีมวิจัย ได้เทรนโมเดล Transformer แบบ Base ซึ่งมีจำนวนพารามิเตอร์ทั้งหมดกว่า 74 ล้านพารามิเตอร์ และใช้ Python library `fairseq` จาก Facebook AI Research [Ott et al. 2019] โดยเทรนโมเดลบน NVIDIA DGX-1 ซึ่งเป็น Cluster ของ GPU NVIDIA V100

ชุดข้อมูลที่ใช้ในการเทรนโมเดลครั้งนี้มาจาก ชุดข้อมูลคู่ประโยคภาษาอังกฤษ-ไทย `(scb-mt-en-th-2020)` ซึ่งมีจำนวน 1,001,752 คู่ประโยค จากแหล่งที่มาต่างๆเช่น การจ้างนักแปลภาษา แปลบทสนทนาจากภาษาอังกฤษเป็นไทย และการ Crawl ข้อมูลจากเว็บไซต์ข่าวหรือองค์กร ที่มีเนื้อหาในทั้งสองภาษา โดยสามารถดูรายละเอียดเพิ่มเติมได้ที่ [English-Thai Machine Translation Dataset](https://airesearch.in.th/releases/machine-translation-datasets)

## ผลการทดสอบ

การเปรียบเทียบ BLEU score และ n-gram precision ระหว่าง ผลการแปลของโมเดล Transformer Base ที่เทรนจาก ชุดข้อมูลคู่ประโยคจาก `scb-mt-en-th-2020` (SCB_1M), ชุดข้อมูลคู่ประโยคจาก Open Parallel Corpus [Tiedemann et al. 2012] ในส่วนที่เป็นคู่ประโยคภาษาอังกฤษและไทย ([mt-opus](https://github.com/vistec-AI/mt-opus)), ชุดข้อมูลคู่ประโยคที่รวมทั้ง `scb-mt-en-th-2020` และ `mt-opus` (SCB_1M + MT_OPUS), ผลการแปลของโมเดลแปลภาษาเฉพาะการแปลจากอังกฤษ→ไทย จาก AI for Thai (aiforthai.in.th) และ ผลการแปลจาก Google Translation API (ทดสอบและวัดผลใน เดือนพฤษภาคม 2020)

สำหรับคู่ประโยคทีใช้ทดสอบ เป็นชุดข้อมูลทดสอบจาก IWSLT 2015 ประกอบด้วย 46 Transcript ที่มีการถอดคำและแปลในภาษาอังกฤษและไทย จาก TED Talk ระหว่างปี 2010 ถึง 2013 (tst2010-2013) รวมเป็น 4,242 ประโยค โดยใช้ SacreBLEU [Post et al. 2018] (case sensitive / case-insentive) สำหรับภาษาอังกฤษเป็น Target language และ BLEU4 [Papineni et al. 2002] สำหรับภาษาไทยเป็น Target language

![Evaluation Result](/assets/img/releases/machine_translation_models/eval_iwslt2015.png)

## ตัวอย่างการใช้ในภาษา Python

```python
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

th2en.translate("งั้นเอาเป็นเวนติ แบล็คแอนด์ไวท์มอคค่าใส่นมสดกับวิปครีม จากสตาร์บัคส์สาขาห้างเบิร์ชวิลล์นะคะ")
```

```
Output:
so a venti black and white mocha with whole milk
and whipped cream from the starbucks at the birchville mall.
```

นอกจากนี้ทางสถาบันฯ ได้เตรียม Jupyter Notebook สำหรับการทดสอบการรันโมเดล Machine Translation ได้โดยทันทีผ่าน [Google Colaboratory](https://colab.research.google.com/drive/1b7Uo9Ic1UltWvC2S7-qqix5WUL-P86xD?usp=sharing)

## เวอร์ชัน

- **Version 1.0 (23 June 2020):** โมเดล Pre-trained Transformer Base ที่เทรนจาก ชุดข้อมูลคู่ประโยคภาษาอังกฤษ-ไทย `scb-mt-en-th-2020` เวอร์ชั่น 1.0

## อ้างอิง

- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. In Advances in neural information processing systems (pp. 5998-6008).
- Ott, M., Edunov, S., Baevski, A., Fan, A., Gross, S., Ng, N., Grangier, D., & Auli, M. (2019). fairseq: A Fast, Extensible Toolkit for Sequence Modeling. NAACL-HLT.
- Tiedemann, J. (2012). Parallel Data, Tools and Interfaces in OPUS. LREC.
- Papineni, K., Roukos, S., Ward, T., & Zhu, W. J. (2002, July). BLEU: a method for automatic evaluation of machine translation. In Proceedings of the 40th annual meeting on association for computational linguistics (pp. 311-318). Association for Computational Linguistics.
- Post, M. (2018). A Call for Clarity in Reporting BLEU Scores. WMT.

## ทดลองใช้โมเดล

<div id="model-demo" class="test1 w-100 d-flex flex-column">  
  <div class="btn-group" role="group" aria-label="Basic example">
    <button type="button" class="btn btn-select-lang border bg-white selected-lang" id="thai-lang">Thai -> English</button>    
    <button type="button" class="btn btn-select-lang border bg-white" id="eng-lang">English -> Thai</button>
  </div>
  <div class="textarea-box d-flex flex-column pb-3">              
    <textarea class="textarea-input py-2 px-3 border data-hj-allow" maxlength="1000" id="textarea-input" rows="5"></textarea>
    <div class="text-right limit-length" id="limit-length">
      <span id="char-lefts">0</span>/1000
    </div>
    <div class="d-flex justify-content-center">
      <button type="button" class="btn btn-translate btn-light border border-secondary mx-3 d-flex justify-content-center align-items-center" id="btn-translate">
        <i class="fa fa-language icon-btn pr-1"></i> Submit
      </button>
      <button type="button" class="btn btn-remove btn-remove-all btn-light border border-secondary mx-3 d-none" id="btn-remove-all">
        <i class="fa fa-trash-alt"></i> Reset
      </button>
      <div class="loading d-none text-center mx-3" id="loading"> 
        <div class="spinner-grow spinner-left" role="status">        
        </div>
        <div class="spinner-grow spinner-center" role="status">        
        </div>
        <div class="spinner-grow spinner-right" role="status">        
      </div>
    </div>
  </div>
  </div>
  <div class="compare-output-container d-flex flex-row mb-2">    
    <div class="textarea-mt-result translate-output d-none flex-column border flex-fill mr-1 w-100">
      <div class="mt-container px-3 pt-2 bg-white border-bottom">
        <div class="mt-title pb-1">Our result</div>
      </div>
      <textarea class="textarea-mt-output p-3 data-hj-allow" id="output-mt-translation" readonly></textarea>
      <div class="feature-output text-right bg-white">
        <button class="btn btn-sm border-0 bg-white btn-features" id="btn-mt-copy" data-toggle="tooltip" data-placement="bottom" title="copy to clipboard">
          <i class="fa fa-clone"></i>
        </button>
      </div>
    </div>    
    <div class="textarea-gt-result translate-output d-none flex-column border flex-fill ml-1 w-100">    
      <div class="gt-container px-3 pt-2 bg-white border-bottom">
        <div class="gt-title pb-1">Result from Google Translate</div>
      </div>
      <textarea class="textarea-gt-output p-3 data-hj-allow" id="output-gt-translation" readonly></textarea>
      <div class="feature-output text-right bg-white">
        <button class="btn btn-sm border-0 bg-white btn-features" id="btn-gt-copy" data-toggle="tooltip" data-placement="bottom" title="copy to clipboard">
          <i class="fa fa-clone"></i>
        </button>
      </div>
    </div>
  </div>  
  <span class="compare-tran text-right d-none" id="compare-translate">
    Compare with <a class="link-google-tran" id="link-google-translate">Google Translate</a>
  </span>	  
</div>

<style>
  textarea { 
    border: 1px solid #ffffff;   
    resize: none;              
  }
  
  textarea:focus {
    outline: none !important;    
  }

  .btn-select-lang {    
    width: 10rem;
    font-size: 0.9rem;
  }

  .btn-select-lang:hover, .btn-select-lang:focus {
    background-color: #52348c !important;
    color: #ffffff;
    box-shadow: none;
    outline: none;    
  }

  .selected-lang {
    background-color: #52348c !important;
    color: #ffffff;
  }

  .btn-remove-all, .btn-translate {   
    transition: all 0.3s;
    background-color: #303030;
    color: #ffffff;
    outline: 0;    
    width: 7rem;
    font-size: 0.9rem;
  }

  .icon-btn {
    font-size: 1.5rem;
  }

  .btn-remove-all {
    background: #ffffff;
    color: #303030;
  }

  .btn-translate:hover, .btn-translate:focus {    
    background: #52348c;
    color: #ffffff;
    transition: all 0.3s;
    box-shadow: none;
  }

  .btn-remove-all:hover, .btn-remove-all:focus {    
    transition: all 0.3s;
    box-shadow: none;
  }

  .btn-feature:hover, .btn-feature:focus {
    border-color: transparent;    
    -webkit-transform: scale(1.2);
    transform: scale(1.2);    
    outline: none;
    box-shadow: none;
  }

  .btn-remove:hover, .btn-remove:focus {    
    outline: none;
    box-shadow: none;
    color: #303030;
  }
  
  .btn-feature {
    color: #303030;
    background-color: #F0F0F0;
    transition: all 0.5s;
    cursor: pointer;    
  }

  .tooltip > .tooltip-inner {    
    font-size: .625rem;
  }

  .spinner-left {
    color: #fff200;
  }

  .spinner-center {
    color: #a6253b;
  }

  .spinner-right {
    color: #52348c;
  }

  .btn-features {
    color: #C5C5C5;
  }

  .btn-features:hover, .btn-features:focus{
    color: #303030;
    outline: none;
    box-shadow: none;
  }

  .mt-title {
    width: 5rem;
    color: #52348c;
    height: 100%;
    border-bottom: 2px solid #52348c;
  }

  .gt-title {
    white-space: nowrap;
    width: 14.5rem;
    border-bottom: 2px solid #4284f3;
    color: #4284f3;
  }

  .catch-error {
    color: #E62020;
    font-size: 0.8rem;
    height: 100%;
  }

  .limit-length {
    font-size: 0.8rem;
    color: #777777;
  }

  @keyframes spinner-grow {
  0% {
    opacity: 0;
    transform: scale(0);
  }
  50% {
    opacity: 1;
  }
  100% {
    opacity: 0;
    transform: scale(1);
  }
}

.spinner-grow {
  position: relative;
  display: inline-block;
  width: 2rem;
  height: 2rem;
  overflow: hidden;
  text-indent: -999em;
  vertical-align: text-bottom;
  background-color: currentColor;
  border-radius: 50%;
  animation-name: spinner-grow;
  animation-duration: .75s;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}

.spinner-grow-sm {
  width: 1rem;
  height: 1rem;
}

.link-google-tran {
  color: #4284f3 !important;
  cursor: pointer;
}

.compare-tran {
  font-size: 0.9rem;  
}

@media screen and (max-width: 500px)   { 
  .compare-output-container {
    flex-direction: column !important;    
  }
  .translate-output {
    margin: 0 !important;
  }
  .btn-translate, .btn-remove-all {
    font-size: 0.8rem;
    width: 6rem;
  }
} 
</style>

<script src="https://cdnjs.cloudflare.com/ajax/libs/axios/0.19.2/axios.min.js"></script>

<!-- Hotjar Tracking Code for https://airesearch.in.th -->
<script>
    (function(h,o,t,j,a,r){
        h.hj=h.hj||function(){(h.hj.q=h.hj.q||[]).push(arguments)};
        h._hjSettings={hjid:1922787,hjsv:6};
        a=o.getElementsByTagName('head')[0];
        r=o.createElement('script');r.async=1;
        r.src=t+h._hjSettings.hjid+j+h._hjSettings.hjsv;
        a.appendChild(r);
    })(window,document,'https://static.hotjar.com/c/hotjar-','.js?sv=');
</script>

<script>
  
  let sl = "th", tl = "en" 

  function sleep(ms) {
    return new Promise(resolve => setTimeout(resolve, ms));
  }

  async function googleApi(input){      
    try {
      const uri = `https://translate.googleapis.com/translate_a/single?client=gtx&sl=${sl}&tl=${tl}&dt=t&q=${encodeURIComponent(input)}`
      const response = await axios.get(uri)         
      return response.data                
    } 
    catch (err) {
      $('#compare-translate').removeClass('d-none')      
      $('#output-gt-translation').addClass('catch-error');         
      $('#output-gt-translation').val(      
      "You have sent too many requests recently." +
      "\n\nPlease try again later or compare directly with google translation website link below."); 
    }
  }

  async function mtApi(input){   
    const input_arr = input.split('\n');    
    const input_json = {
      text: input_arr,
      source: sl,
      target: tl
    }          
    try {      
      const response = await axios.post('https://mt-api.airesearch.in.th', JSON.stringify(input_json), {                  
        headers: {                            
          'Content-Type': 'application/json',  
        }               
      })
      return response.data
    } catch (err) {             
      $('#output-mt-translation').addClass('catch-error');            
      $('#output-mt-translation').val(
      "You have sent a request for exceeding the limit rate." + 
      "\n\nPlease try again in a few seconds.");       
    }    
        
  }

  async function translate() {
    $('#loading').removeClass('d-none')    
    $('#btn-remove-all').addClass('d-none')
    $('#btn-translate').removeClass('d-flex').addClass('d-none')
    $('#compare-translate').addClass('d-none')         

    const input = $('#textarea-input').val()    
    const [dataArrMT, dataArrGT] = await Promise.all([mtApi(input) ,googleApi(input)]);  
    
    var resultGT = '', resultMT = ''      
    for(var i = 0; i < dataArrGT[0].length; i++){
      resultGT += dataArrGT[0][i][0]        
    }      
    for(var item of dataArrMT) {
      resultMT += item 
      resultMT += '\n' 
    }    
    
    await sleep(1200);
    if(resultGT) {
      $('#output-gt-translation').removeClass('catch-error');         
      $('#output-gt-translation').val(resultGT)
    }
    if(resultMT) {
      $('#output-mt-translation').removeClass('catch-error');
      $('#output-mt-translation').val(resultMT)
    }
                
  }
  $('#thai-lang').click(function() {
    sl = "th"
    tl = "en"
    $('#eng-lang').removeClass('selected-lang')
    $(this).addClass('selected-lang')
  })

  $('#eng-lang').click(function() {
    sl = "en"
    tl = "th"
    $('#thai-lang').removeClass('selected-lang')
    $(this).addClass('selected-lang')
  })

  function change_class() {     
    $('#output-gt-translation').val('')
    $('#output-mt-translation').val('')
    $('#btn-translate').removeClass('d-none').addClass('d-flex')   
    $('#output-gt-translation').height('auto')
    $('#output-mt-translation').height('auto')              
  }
  
  $(document).ready(function(){
    $('[data-toggle="tooltip"]').tooltip();           
  });

  $('input[type="text"], textarea').on('input', function () {
    change_class()
  });

  $('.btn-remove').click(function(){
    $("#textarea-input").val('');
    change_class() 
  })

  $('#btn-mt-copy').click(function() {    
    var copyText = $('#output-mt-translation')[0]
    copyText.select();
    copyText.setSelectionRange(0, 99999)
    document.execCommand("copy");    
  })

  $('#btn-gt-copy').click(function() {    
    var copyText = $('#output-gt-translation')[0]
    copyText.select();
    copyText.setSelectionRange(0, 99999)
    document.execCommand("copy");    
  })

  $('#btn-translate').click(async function() {         
    if($("#textarea-input").val().trim() !== ''){
      change_class()
      await translate();  
      $('#loading').addClass('d-none')              
      $('.translate-output').removeClass('d-none')   
      $('.translate-output').addClass('d-flex')   
      const outpuGT = $('#output-gt-translation')
      const outpuMT = $('#output-mt-translation')
      const heightGT = outpuGT[0].scrollHeight-20
      const heightMT = outpuMT[0].scrollHeight-20
      if(heightGT > heightMT) {                
        outpuGT.height(heightGT+'px')        
        outpuMT.height(heightGT+'px')
      } else {                
        outpuMT.height(heightMT+'px')
        outpuGT.height(heightMT+'px')
      }    
      $('#btn-remove-all').removeClass('d-none')  
      $('#btn-translate').removeClass('d-none').addClass('d-flex') 
    } 
  })

  $('#link-google-translate').click(function() {    
    const input = $("#textarea-input").val()
    window.open(
      `https://translate.google.co.th/#view=home&op=translate&sl=${sl}&tl=${tl}&text=${input}`
      ,
      '_blank' 
    );
  })

  $('#textarea-input').on("input keyup", function(){    
    $(this).height('auto')    
    if($(this)[0].scrollHeight >= 157){
      $(this).height(this.scrollHeight+'px')      
    } 

    var currentLength = $(this).val().length;
    var maxLength = $(this).attr('maxlength');    
    if(currentLength >= maxLength) {                    
      $('#limit-length').css('color', '#E62020');    
    }else {
      $('#limit-length').css('color', '#777777');    
    }
    $('#char-lefts').text(currentLength)    
        
  });
</script>
