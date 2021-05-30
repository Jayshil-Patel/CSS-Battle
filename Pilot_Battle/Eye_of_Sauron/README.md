# Eye of Sauron
<img src="https://cssbattle.dev/targets/11.png">

```HTML
<div></div>
<style>
  body{
    background:#191210;
  }
  div{
    background:#84271C;
    height:50px;
    width:50px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    border-radius:50%;
    border:25px solid #191210;
    box-shadow:0 0 0 20px #ECA03D;
  }
  div:before,div:after{
    content:'';
    position:absolute;
    height:50px;
    width:100px;
    box-sizing:border-box;
    border:20px solid #ECA03D;
  }
  div:after{
    border-bottom-left-radius:110px;
    border-bottom-right-radius:110px;
    top:25;
    right:75;
    border-top:0;
  }
    div:before{
    border-top-left-radius:110px;
    border-top-right-radius:110px;
    top:-25;
    left:75;
    border-bottom:0;
  }
</style>
```