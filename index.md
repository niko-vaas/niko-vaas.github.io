<style>
h1.textstyle {
    font-family: 'Courier New', monospace;
}
</style>

# HinderD.

Hindering drug abuse, one word at a time.    <span id="cursor">|</span>

[Contribute. Every dollar helps.](https://gofund.me/2f507f1a)
[Our blog. Watch us build VAaS.](blog.hinderd.org)


<script>
    var cursor = true;
    var speed = 250;
    setInterval(() => {
      if(cursor) {
        document.getElementById('cursor').style.opacity = 0;
       cursor = false;
       }else {
        document.getElementById('cursor').style.opacity = 1;
        cursor = true;
      }
    }, speed);
</script>
