# Eye of The Tiger
<img src="https://cssbattle.dev/targets/16.png">

```HTML
<div></div>
<style>
  body{
    background:#0B2429;
  }
  div{
    top:100px;
    left:80px;
    position:absolute;
    height:100px;
    width:100px;
    background:#998235;
    transform:rotate(45deg);
    box-shadow:100px -100px 0 0 #998235;
  }
    div:before{
	top: -100px;
	position: absolute;
	content: "";
	border-radius: 50%;
	height: 180px;
	width: 180px;
	background: #0B2429;
	z-index: 2;
	border: 10px solid #998235;
  }
  div:after{
    left:30px;
    top:-70px;
    position:absolute;
    content: "";
    border-radius: 50%;
    height: 50px;
    width: 50px;
    background: #0b2429;
    z-index: 3;
    border: 45px solid #f3ac3c;}
</style>
```