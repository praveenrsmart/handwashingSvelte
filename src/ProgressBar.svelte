<script>
    export let progress=20;

</script>
<style>
    
</style>
<div bp="grid">
    <div bp="offset-5@md 4@md 12@sm" class="progress-container" style=" margin:20px 0; border:solid rgb(194,194,194) 1px;">
      <div class="progress-bar" style="width:{progress}%; height:30px; background-color: rgb(77,199,55);">
          <span class="sr-only">%{progress}</span>
      </div>  
    </div>
</div>