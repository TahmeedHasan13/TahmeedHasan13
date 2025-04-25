<div align="center"> 
  <p>Visitor count</p>
  <img src="https://profile-counter.glitch.me/TahmeedHasan13/count.svg" alt="Visitor's Count" />
</div>
<span id="visits" style="color: #FF5733; font-weight: bold;">Loading...</span>
<script>
  fetch('https://api.countapi.xyz/hit/TahmeedHasan13.github.io/visits')
    .then(res => res.json())
    .then(res => {
      document.getElementById('visits').innerText = res.value;
    });
</script>
