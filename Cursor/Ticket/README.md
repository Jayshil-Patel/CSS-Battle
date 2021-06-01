# Ticket
<img src="https://cssbattle.dev/targets/20.png">

```HTML
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<style>
  body {
    background: #62306d;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    position: absolute;
  }
  #a {
    height: 100px;
    width: 80px;
    background: #f7ec7d;
    box-shadow: 60px 0 0 0 #e38f66, -60px 0 0 0#F7EC7D;
  }
  #b,
  #c {
    border-radius: 50%;
    z-index: 2;
  }
  #b {
    background: #62306d;
    height: 20px;
    width: 20px;
    top: 90;
    left: 230;
    box-shadow: 0 100px 0 0 #62306d;
  }
  #c {
    background: #62306d;
    height: 40px;
    width: 40px;
    top: 80;
    left: 80;
    box-shadow: 0 100px 0 0 #62306d, 200px 100px 0 0 #62306d,
      200px 0 0 0 #62306d;
  }
</style>

```