# Cloaked Spirits
<img src="https://cssbattle.dev/targets/10.png">

```HTML
<div id="c"></div>
<div id="d"></div>
<style>
  body{
    background:#62306D;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  div{
    position:absolute;
    height:60px;
    width:60px;
  }
  #c{
    background:#AA445F;
    border-radius:50%;
    top:50px;
    border: 20px solid #E38F66;
  }
  #c::after{
    content:"";
    position:absolute;
    top:80;
    left:80;
    background:#E38F66;
    height:60px;
    width:60px;
    border-radius:50%;
    border: 20px solid #AA445F;
  }
    #c::before{
    content:"";
    position:absolute;
    top:80;
    right:80;
    background:#E38F66;
    height:60px;
    width:60px;
    border-radius:50%;
    border: 20px solid #AA445F;
  }
  #d{
    height:200px;
    width:100px;
    background:#F7EC7D;
    bottom:0;
    z-index:-1;
    box-shadow:-100px 100px 0 #F7EC7D,100px 100px 0 #F7EC7D;
  }
  

</style>
```