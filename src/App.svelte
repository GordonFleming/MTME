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
    <br><br>
    <h1>who we are</h1>
    <div transition:scale="{{ duration: 2000, delay: 2000}}" class="pad-top">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-sm-12">
                    <img class="img-fluid" src="portrait_One.webp" alt="portrait_image" height="1000vh" width="680vw">
                    <p class="pt-4">We eventually left the makeup industry to pursue Jobs In the field in which we studied – Biotechnology.</p>
                    <p>Yet our passion for makeup never left us and as a side hustle we did some freelancing makeup Jobs.</p>
                    <p>The Beauty Industry really ignited the passion within us , to push our creativity to the next level and enhance our artistry skill.</p>
                </div>
                <div class="col-md-6 col-sm-12">
                    <p>We are the <strong>Mack Twins</strong>, Chanel & Charnay Mack , professional freelance makeup artists.</p>
                    <p><strong>Welcome to our Makeup Website</strong></p>
                    <p class="pb-4">Our makeup Artistry journey started in the year 2013, while studying towards our Bsc degrees. We were approached by @elizabetharden to promote their new lipstick line , and from there got approached by @bobbibrown and worked there for 2 years and then @maccosmeticsafrica for another 2 years and lastly @urbandecaycosmetics .</p>
                    <img class="img-fluid" src="portrait_Two.webp" alt="portrait_image" height="1000vh" width="680vw">
                </div>
            </div>
        </div>
    </div>

    <div class="">
        <br>
        <p><strong>All women want to feel beautiful and we want to  ignite that feeling in each and everyone of</strong></p>
        <h3><strong>YOU</strong></h3>
        <br>
        <h2>Mack Twins</h2>
    </div>

    <center><img class="img-fluid" transition:scale="{{ duration: 2000, delay: 3000}}" src="portrait_Three.webp" alt="portrait_image" height="800vh" width="1000vw"></center>
</div>