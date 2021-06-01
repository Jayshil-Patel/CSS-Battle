# Cube

<img src="https://cssbattle.dev/targets/19.png">

```HTML
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<style>
  *{background:#0B2429;}
  div{position:absolute;}
  #a{
    height:100px;
    width:100px;
    background:#F3AC3C;
    top:50%;left:50%;
    transform: translate(-50%,-15%) rotate(45deg);
  }
  #b,#c{
    height:70px;
    width:70px;
    top:80;
  }
  #b{
    background:#998235;
    left:50%;
    transform:translateX(-100%) skewY(-45deg);
  }
  #c{
    background:#1A4341;
    right:50%;
    transform:translateX(100%) skewY(45deg);
    }

</style>
```