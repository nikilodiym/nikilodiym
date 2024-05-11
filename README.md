<h1 style="color:blue; font-size:40px;" id="main-text">Hi Everyone, I'm Nikita</h1>
<p>This is a nice and understandable text.</p>
<script>
  window.onload = function() {
    var text = document.getElementById('main-text');
    var str = text.textContent;
    var i = 0;
    var timer = setInterval(function() {
      text.textContent = str.slice(0, i);
      i++;
      if (i > str.length) {
        clearInterval(timer);
        setTimeout(function() {
          text.textContent = "Go to my profile";
        }, 1000);
      }
    }, 100);
  };
</script>
![github-contribution-grid-snake-dark](https://github.com/nikilodiym/nikilodiym/assets/134860909/fb658821-008e-4503-8c86-3fe9253778b8)
