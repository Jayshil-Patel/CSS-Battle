# Ups n Downs
<img src="https://cssbattle.dev/targets/4.png">

```HTML
<div id="a"></div>
<style>*{background:#62306D;}
  div,div::after,div::before{
    background:#F7EC7D;
    height:100px;
    width:100px;
    display:inline-block;
    margin:42px 142px;
    border-radius:50% 50% 0 0;   
  }
  div::after,div::before{
    content:"";
    border-radius:0 0 50% 50%;
    margin:100px -100px;
  }
  div::after{
    margin:-200px 100px;
  }
</style>
```