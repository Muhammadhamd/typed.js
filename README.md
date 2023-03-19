<center><h1>Typed.js</h1></center>

<p>Typed.js is a library that types. Enter in any string, and watch it type at the speed you've set, backspace what it's typed, and begin a new sentence for however many strings you've set.</p>

<h3>This is the link that you have to paste at the bottom of the page.</h3>


 <pre><span><script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script></span></pre>
 <br> <br> <br>
 
 <h3> <b>source Code</b></h3>
 <pre>  <span class="pl-c">&lt;!-- Element to contain animated typing --&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">span</span> <span class="pl-c1">id</span>="<span class="pl-s">element</span>"<span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">span</span><span class="pl-kos">&gt;</span>



  
<script>
<span style="color:blue;">Let = element = document.getElementById("element");</span>



 <span class="pl-c">&lt;!-- Setup and start animation! --&gt;</span>
  let typed = new Typed(".element",{
    strings:["Frontend Developer",  "MERN Developer","Graphic Designer","Freelancer","Bloger"],
    typeSpeed:80,
    backSpeed:80,
    backdelay:1000,
    loop:true
})
</script>
  <span class="pl-c">&lt;!-- Load library from the CDN --&gt;</span>
  <span class="pl-kos">&lt;</span><span class="pl-ent">script</span> <span class="pl-c1">src</span>="<span class="pl-s"><script https://cdn.jsdelivr.net/npm/typed.js@2.0.12</span>"<span class="pl-kos">&gt;</span><span class="pl-kos">&lt;/</span><span class="pl-ent">script</span><span class="pl-kos">&gt;</span>
</pre>
