<script>
    export let count;
</script>
<div class ="options">
    <form>
      <p><b>Filter Results:</b></p>
     <label for="normal">
       <input type="radio" id="normal" name="fav_language" value="Normal"> Normal
     </label><br>
  
     <label for="greyscale">
          <input type="radio" id="greyscale" name="fav_language" value="Greyscale"> Greyscale
     </label><br>
  
     <label for="blur">
          <input type="radio" id="blur" name="fav_language" value="blur"> Blur
     </label><br>
  
     <label for="both">
      <input type="radio" id="greyscale and blur" name="fav_language" value="greyscale and blur"> Greyscale and Blur
  </label><br>
  </form>
  <div class="Counter">
    <p><b>Number of Photos Needed:</b></p>
    <button>Red</button>
    <span>{ count }</span>
  </div>
</div>

<slot />