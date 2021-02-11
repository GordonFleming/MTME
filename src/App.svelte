<script>
    import {fade, slide, scale} from 'svelte/transition';
    import Inview from 'svelte-inview';
    let ref1;
    let ref2;
    let ref3;

    let time = false;

    function timeOut(){
        time = true;
    }
    setTimeout(timeOut, 2500);
</script>

<!-- Cover image -->

<div id="cover" in:slide="{{ duration: 2500 }}" />

<!-- Main -->
{#if time}
<Inview
    let:inView={inView}
    wrapper={ref1}
    rootMargin="-50px"
    unobserveOnEnter={true}
    >
    <div bind:this={ref1}>
        {#if inView}
            <div transition:fade="{{ duration: 500, delay: 200}}">
                <div class="container text-center mb-5">
                    <div class="row">
                        <div>
                        <a href="https://www.facebook.com/mtme.macktwins.1" target="_blank"><i id="facebook" class="fab fa-facebook-square fa-4x"></i></a>
                        <a href="https://www.youtube.com/channel/UC91OgmMT9nhFcjjDEfmJy-w" target="_blank"><i id="youtube" class="fab fa-youtube fa-4x"></i></a>
                        <a href="https://instagram.com/macktwinsmakeup" target="_blank"><i id="insta" class="fab fa-instagram-square fa-4x"></i></a>
                        <a href="http://www.linkedin.com/company/mack-twins-makeup/" target="_blank"><i id="linkedin" class="fab fa-linkedin fa-4x"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        {/if}
    </div>
</Inview>

<Inview
    let:inView={inView}
    wrapper={ref2}
    rootMargin="-50px"
    unobserveOnEnter={true}
    >
    <div bind:this={ref2}>
        {#if inView}
            <h1>who we are</h1>
            <div transition:scale="{{ duration: 1000, delay: 1300 }}" class="pad-top">
                <div class="container">
                    <div class="row">
                        <div class="col-md-6 col-sm-12">
                            <p class="p-top">We are the <strong>Mack Twins</strong>, Chanel & Charnay Mack , professional freelance makeup artists.</p>
                            <p class="p-top"><strong>Welcome to our Makeup Website</strong></p>
                            <p class="pb-4 p-top">Our makeup Artistry journey started in the year 2013, while studying towards our Bsc degrees. We were approached by @elizabetharden to promote their new lipstick line , and from there got approached by @bobbibrown and worked there for 2 years and then @maccosmeticsafrica for another 2 years and lastly @urbandecaycosmetics .</p>
                            <img class="img-fluid" src="/images/portrait_Two.webp" alt="portrait_image" height="1000vh" width="680vw">
                        </div>
                        <div class="col-md-6 col-sm-12">
                            <img class="img-fluid mt-4 mt-md-0" src="/images/portrait_One.webp" alt="portrait_image" height="1000vh" width="680vw">
                            <p class="pt-4 p-top">We eventually left the makeup industry to pursue Jobs In the field in which we studied – Biotechnology.</p>
                            <p class="p-top">Yet our passion for makeup never left us and as a side hustle we did some freelancing makeup Jobs.</p>
                            <p class="p-top">The Beauty Industry really ignited the passion within us , to push our creativity to the next level and enhance our artistry skill.</p>
                        </div>
                    </div>
                </div>
            </div>
        {/if}
    </div>
</Inview>
    

<Inview
    let:inView={inView}
    wrapper={ref3}
    rootMargin="-50px"
    unobserveOnEnter={true}
    >
    <div bind:this={ref3}>
        {#if inView}
            <div class="container">
                <div class="row mt-5">
                    <div class="col-12">
                        <p class="p-top"><strong>All women want to feel beautiful and we want to  ignite that feeling in each and everyone of</strong></p>
                        <h3><strong>YOU</strong></h3>
                        <br><br><br>
                        <h2>Mack Twins</h2>
                        <h3>Make Up Services</h3>
                        <br>
                        <div class="row">
                            <div transition:scale="{{ duration: 1200, delay: 3000}}" class="col-md-4 col-sm-12">
                                <center><img class="img-fluid" src="/images/weddings.webp" alt="portrait_image" height="800vh" width="1000vw"></center>
                                <h4>Weddings</h4>
                                <br>
                                <p>
                                    <strong>MACK TWINS</strong> provide a make up experience to the bridal entourage that brings beauty and radiance on this special day of the Bride.
                                </p>
                            </div>
                            <div transition:scale="{{ duration: 1400, delay: 3400}}" class="col-md-4 col-sm-12">
                                <center><img class="img-fluid" src="/images/portrait_Three.webp" alt="portrait_image" height="800vh" width="1000vw"></center>
                                <h4>Special Occasions</h4>
                                <br>
                                <p>
                                    Your Anniversary , Your Party , Your Event , Your Special Day is where <strong>MACK TWINS</strong> bring out and ignite the beauty in YOU through makeup.
                                </p>
                            </div>
                            <div transition:scale="{{ duration: 1600, delay: 3600}}" class="col-md-4 col-sm-12">
                                <center><img class="img-fluid" src="/images/portrait_Two.webp" alt="portrait_image" height="800vh" width="1000vw"></center>
                                <h4>Matric Balls</h4>
                                <br>
                                <p>A celebration of knowledge and beauty. This is where <strong>MACK TWINS</strong> brings out the magic of YOUR beauty to the world You are entering.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        {/if}
    </div>
</Inview>
{/if}

<div class="container">
    <h1 class="pt-5">Pricing</h1>
    <center> <a href="/documents/pricing.pdf" target='_blank'><button id="pricing" class="btn-primary">View / Download</button></a></center>
</div>

<div class="container mt-5">
    <h2>Season 1 Episode 1 , 2 & 3 : MakeUp Basics for Beginners</h2>
    <div class="mt-4">
        <p id="youtube-text">The <strong>MACK TWINS</strong> Season 1 tutorials  focuses on MakeUp Basics for Beginners.</p>
        <p id="youtube-text">We want to make MakeUp easy for everyone of YOU. Please let us know if these tutorials were of any help on INSTA @macktwinsmakeup.</p>
        <p id="youtube-text"><strong>MACK TWINS</strong> will also appreciate it if you could LIKE , SUBSCRIBE and SHARE. Please switch on your notification buttons so that you can be notified the moment we publish a new video . Keep well , Keep Safe under Covid19.</p>
    </div>
    
    <div class="row mt-5 text-center">
        <div class="col-lg-4 col-md-12 col-sm-12">
            <iframe title="1" width="350" height="200" src="https://www.youtube.com/embed/h3GjmEXP5k0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
            <iframe title="2" width="350" height="200" src="https://www.youtube.com/embed/aDrQFx7bzf8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
            <iframe title="3" width="350" height="200" src="https://www.youtube.com/embed/TX9xK_IvdO8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
    <div class="row mt-5 text-center">
        <div class="col-lg-4 col-md-12 col-sm-12">
            <iframe title="4" width="350" height="200" src="https://www.youtube.com/embed/--ZKf-k7E2w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
            <iframe title="5" width="350" height="200" src="https://www.youtube.com/embed/hWHYxq6xAkk"frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</div>