# Overlap
<img src="https://cssbattle.dev/targets/15.png">

```HTML
<div></div>
<div></div>

<style>
  body{
    background:#09042A;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  div{
    position:absolute;
    height:150px;
    width:150px;
    border-radius:50%;
  }
  div:nth-of-type(1){
    left:75px;
    background:#7B3F61;
  }
  div:nth-of-type(2){
    left:175;
    background:#E78481;
    overflow:hidden;
  }
  div:nth-of-type(2):before{
    content:'';
    background:#09042A;
    height:100%;
    width:100%;
    left:-100px;
    border-radius:50%;
    position:absolute;
  }

</style>
```