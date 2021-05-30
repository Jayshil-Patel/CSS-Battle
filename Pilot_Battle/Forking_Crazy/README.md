# Forking Crazy
<img src="https://cssbattle.dev/targets/8.png">

```HTML
<div id="a"></div>
<div class="ball"></div>
<div id="b"></div>
<style>
  body{
    display:flex;
    justify-content:center;
    align-items:center;
    background:#6592CF;    
  }
  #a{
    position:absolute;
    bottom:0px;
    width:20px;
    height:100px;
    background:#060F55;
    box-shadow:-60px -140px 0 #060F55,-20px -140px 0 #060F55,20px -140px 0 #060F55,60px -140px 0 #060F55;
  }
  #b{
    background:#060F55;
    height:100px;
    width:140px;
    position:absolute;
    bottom:50px;
    border-radius:0 0 70px 70px;
  }
  .ball{
    position:absolute;
    height:20px;
    width:20px;
    border-radius:50%;
    background:#6592CF;
    z-index:1;
    box-shadow:-40px 0 0 #6592CF,40px 0 0 #6592CF,0 0 0 #6592CF,-60px -90px 0 #060F55,-20px -90px 0 #060F55,20px -90px 0 #060F55,60px -90px 0 #060F55;
  }
</style>
```