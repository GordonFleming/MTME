<script>
    import {fade, slide, scale} from 'svelte/transition';
</script>

<div id="cover" in:slide="{{ duration: 2500 }}">

</div>
<!-- Main -->
<div transition:fade="{{ duration: 2000, delay: 1800}}">
    <center>
        <a href="https://www.facebook.com/mtme.macktwins.1" target="_blank"><i id="facebook" class="fab fa-facebook-square fa-5x"></i></a>
        <a href="https://www.youtube.com/channel/UC91OgmMT9nhFcjjDEfmJy-w" target="_blank"><i id="youtube" class="fab fa-youtube fa-5x"></i></a>
        <a href="https://instagram.com/macktwinsmakeup" target="_blank"><i id="insta" class="fab fa-instagram-square fa-5x"></i></a>
    </center>
    
    <div transition:scale="{{ duration: 2000, delay: 2000}}" class="pad-top">
        <div class="row center">
            <div class="col">
                <img src="portrait_One.jpg" alt="portrait_image" height="1000vh" width="680vw">
            </div>
            <div class="col down">
                <img src="portrait_Two.jpg" alt="portrait_image" height="1000vh" width="680vw">
            </div>
        </div>
    </div> 

    <div class="">
        <h1>who we are</h1>
    </div>

    <center><img transition:scale="{{ duration: 2000, delay: 3000}}" src="portrait_Three.jpg" alt="portrait_image" height="800vh" width="1000vw"></center>
</div>