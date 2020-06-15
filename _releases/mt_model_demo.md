---
title: Machine Translation Model (with Demo)
description: Demonstration of the Machine Translation Model
version: 1.0.0
items:
  - item: apdf.csv
    description: "Something blah blah"
    size: 20M
    href: https://download.xyz.com/apdf.csv
    sha256: d8e723c456d0ed1b4c7f715950ff24b080c65bb0289a33bf06e446781b83e1e7
  - item: assorted_government.csv
    description: "Blah blah blah blah"
    size: 37M
    href: https://download.xyz.com/assorted_government.csv
    sha256: 5464346fe176bd1ba55f86d0264c9c89ea8256d52cb07f831f719847a8607b34
order: 2
date: "1 June 2020"
featured: true
image: '/assets/img/releases/letters.jpg'
---

# Story of our model

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed lacinia magna a est faucibus consectetur. Nullam tristique scelerisque turpis. Aenean rutrum urna ac eros rhoncus, sed mollis neque consequat. Aliquam a mauris in nisi commodo dictum quis a mauris. Duis malesuada eu mi in varius. Mauris convallis dui et facilisis condimentum. Pellentesque pellentesque, orci quis fringilla mollis, elit lacus viverra diam, efficitur consequat diam justo sollicitudin mi. Donec gravida eros non congue laoreet. Donec molestie imperdiet metus, id laoreet ante vulputate ut. Praesent quis ultricies neque. Aenean non vehicula massa. Duis velit velit, venenatis sit amet elementum accumsan, auctor sed tortor.

Pellentesque pharetra vehicula lacus, convallis semper felis ultricies in. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Sed commodo mattis tortor, quis fermentum risus pharetra ac. Nulla laoreet ante mauris, ut pretium felis posuere et. Vestibulum cursus lectus vitae purus efficitur elementum. Mauris ut vehicula quam, eu commodo ligula. Vivamus imperdiet elementum odio tempor commodo. Fusce eros velit, volutpat non vehicula ac, pretium nec erat. Donec maximus mi mauris, nec facilisis ante interdum ac. Proin ac ligula metus. Maecenas mauris tortor, egestas efficitur tincidunt nec, sagittis a ex. Pellentesque eu vestibulum lacus. Morbi hendrerit ante ac ligula vestibulum, quis lacinia nunc vestibulum. Praesent laoreet neque et mauris placerat, sit amet pellentesque risus malesuada.

# Test the model

<div class="test1 w-100 d-flex flex-column">
  <div class="textarea-box input-box text-center d-flex flex-column pt-2 pb-3 px-3">    
    <span>
      Translate from
      <strong class="lang-input fade-in">Thai</strong>
    </span>
    <textarea class="textarea-input" id="exampleFormControlTextarea5" rows="5"></textarea>
  </div>
  <div class="text-center down-box">
    <button class="btn btn-convert">
        <i class="fas fa-long-arrow-alt-up icon-up"></i>
        <i class="fas fa-long-arrow-alt-down icon-down"></i>
    </button>
  </div> 
  <div class="textarea-box output-box text-center d-flex flex-column py-2 px-3">
    <span>
      to
      <strong class="lang-output fade-in">English</strong>
    </span>
    <textarea class="textarea-output" id="output-translation" rows="5"></textarea>
    <div class="feature-output text-right mt-2">
      <a class="mr-2" data-toggle="tooltip" data-placement="bottom" title="copy to clipboard">
        <i class="fa fa-clone"></i>
      </a>
      <a class="" data-toggle="tooltip" data-placement="bottom" title="save as .txt file">
        <i class="fa fa-download"></i>
      </a>
    </div>
  </div>
</div>

<style>
  .textarea-box {
    background-color: #F0F0F0;
  }

  textarea { 
    /* height: 140px; 
    min-height: 140px;  
    max-height: 140px; */
    resize: none;
    border: 1px solid #ffffff;
    border-radius: .25rem;
    box-shadow: 0 0 5px #eeeeee;
  }
  textarea:focus {
    outline: none !important;
    border: 1px solid #393939;    
  }

  .btn-convert {
    margin: 5px; 
    transition: all 0.5s;
    cursor: pointer;
    background-color: #F5F5F5;  
    font-size: 18px;     
  }

  .btn-convert:hover, .btn-convert:focus, .btn-feature:hover, .btn-feature:focus {
    border-color: transparent;    
    -webkit-transform: scale(1.2);
    transform: scale(1.2);
    outline: none;
    box-shadow: none;
  }

  .feature-output {
    float: right;
  }

  .btn-feature {
    color: #303030;
    background-color: #F0F0F0;
    transition: all 0.5s;
    cursor: pointer;
    margin: 2px; 
  }

  .tooltip > .tooltip-inner {    
    font-size: 10px;
  }

  strong {
    transition: opacity 0.5s linear;
  }

  .lang-input {
    transform: rotate(45deg);
  }

  .fade-in {
    animation: fadeIn ease 5s;
    -webkit-animation: fadeIn ease 5s;
    -moz-animation: fadeIn ease 5s;
    -o-animation: fadeIn ease 5s;
    -ms-animation: fadeIn ease 5s;
  }


  @keyframes fadeIn{
    0% {
      opacity:0;
    }
    100% {
      opacity:1;
    }
  }

  @-moz-keyframes fadeIn {
    0% {
      opacity:0;
    }
    100% {
      opacity:1;
    }
  }

  @-webkit-keyframes fadeIn {
    0% {
      opacity:0;
    }
    100% {
      opacity:1;
    }
  }

  @-o-keyframes fadeIn {
    0% {
      opacity:0;
    }
    100% {
      opacity:1;
    }
  }

  @-ms-keyframes fadeIn {
    0% {
      opacity:0;
    }
    100% {
      opacity:1;
    }
  }

</style>

<script>
  $(document).ready(function(){
    $('[data-toggle="tooltip"]').tooltip();   
  });

  $('.btn-copy').click(function() {    
    var copyText = document.getElementById('output-translation');
    copyText.select();
    copyText.setSelectionRange(0, 99999)
    document.execCommand("copy");    
  })

  $('.btn-savetxt').click(function() {
    var outputTxt = $('#output-translation').val(); 
    if(outputTxt == null){
      
    }  
  })

  $('.btn-convert').click(function() {
    console.log('click');
    if($('.lang-input').text() == 'Thai') {
      $('.lang-input').html('English', function() {
        $('.lang-input').addClass("fade-in");
      });
      $('.lang-output').html('Thai');
    }else {
      $('.lang-input').html('Thai');
      $('.lang-output').html('English');
    }

  })
    
</script>
