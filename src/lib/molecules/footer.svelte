<script>


</script>

<section>

  <nav class="footer">

  <img src="assets\visual-thinking-logo-footer.svg" alt="footer-logo">

  <ul class="footer-menu">
    <li>Over</li>
    <li>Artikelen</li>
    <li>Tekemethodes</li>
    <li>Kennisclips</li>
  </ul>

  <ul class="social-media">
  <h4>Contact</h4>
  <img src="assets\social-media-icons\instagram.svg" alt="instagram">
  <img src="assets\social-media-icons\youtube.svg" alt="youtube">
  <img src="assets\social-media-icons\instagram.svg" alt="instagram">
  <h5>© Charley Muhren, 2022</h5>
  </ul>

  </nav>
  
</section>

<style>

:root {
    --vtPrimaryFont: "rigid-square", sans-serif;
    --vtSecondaryFont: "yrsa", serif;
}

.footer {
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    align-items: center;
    gap: 10px; 
    background-color: rgb(240, 240, 240);
}

li {
    list-style-type: none;
}

img {
    grid-column: 1;
    margin-left: 3em;
}

.footer-menu {
    grid-column: 2;
    margin-left: 5em;
}

.social-media {
    grid-column: 3;
    
}

@media (max-width: 920px) { 
.footer {
    display: grid;
    grid-template-columns: repeat(1, 1fr); 
    grid-template-rows: repeat(3, 1fr);
    align-items: center;
    gap: 10px;
    margin-left: 1em;
}

img {
    grid-column: 1;
    grid-row: 1;
}

.footer-menu {
    grid-column: 1;
    grid-row: 2;
}

.social-media {
    grid-column: 1;
    grid-row: 3;
}
}

</style>