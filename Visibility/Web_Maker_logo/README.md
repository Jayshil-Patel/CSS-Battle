# Web Maker Logo
<img src="https://cssbattle.dev/targets/14.png">

```HTML
<div></div>
<div></div>
<div></div>
<div></div>
<style>body{background:#F2F2B6;}
  div{
    height:0;width:0;
    border-style:solid;
    position:absolute;
    top:50%;
  }
  div:nth-of-type(1){
    left:50%;
    transform:translate(-140px, -50%);
    border-width:130px 75px 0 75px;
    border-color:#FF6D00 transparent transparent;
    z-index:2;
  }
  div:nth-of-type(2){
    left:50%;
    transform:translate(-120px, -50%);
    border-width:130px 75px 0 75px;
    border-color:#FD4602 transparent transparent;
  }
  div:nth-of-type(3){
    right:-10%;
    transform:translate(-120px, -50%);
    border-width:0 75px 130px 75px;
    border-color:transparent transparent #FD4602;
    z-index:2;
  }div:nth-of-type(4){
    right:-15%;
    transform:translate(-120px, -50%);
    border-width:0 75px 130px 75px;
    border-color:transparent transparent #FF6D00;
  }

</style>
```