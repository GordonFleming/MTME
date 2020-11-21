<script>
    import {fade, slide, scale} from 'svelte/transition';
</script>

<!-- Cover image -->

<div id="cover" in:slide="{{ duration: 2500 }}"></div>

<!-- Main -->
<div transition:fade="{{ duration: 2000, delay: 1800}}">
    <center>
        <a href="https://www.facebook.com/mtme.macktwins.1" target="_blank"><i id="facebook" class="fab fa-facebook-square fa-5x"></i></a>
        <a href="https://www.youtube.com/channel/UC91OgmMT9nhFcjjDEfmJy-w" target="_blank"><i id="youtube" class="fab fa-youtube fa-5x"></i></a>
        <a href="https://instagram.com/macktwinsmakeup" target="_blank"><i id="insta" class="fab fa-instagram-square fa-5x"></i></a>
    </center>
    <br><br>
    <h1>who we are</h1>
    <div transition:scale="{{ duration: 2000, delay: 2200}}" class="pad-top">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-sm-12">
                    <img class="img-fluid" src="portrait_One.webp" alt="portrait_image" height="1000vh" width="680vw">
                    <p class="pt-4 p-top">We eventually left the makeup industry to pursue Jobs In the field in which we studied – Biotechnology.</p>
                    <p class="p-top">Yet our passion for makeup never left us and as a side hustle we did some freelancing makeup Jobs.</p>
                    <p class="p-top">The Beauty Industry really ignited the passion within us , to push our creativity to the next level and enhance our artistry skill.</p>
                </div>
                <div class="col-md-6 col-sm-12">
                    <p class="p-top">We are the <strong>Mack Twins</strong>, Chanel & Charnay Mack , professional freelance makeup artists.</p>
                    <p class="p-top"><strong>Welcome to our Makeup Website</strong></p>
                    <p class="pb-4 p-top">Our makeup Artistry journey started in the year 2013, while studying towards our Bsc degrees. We were approached by @elizabetharden to promote their new lipstick line , and from there got approached by @bobbibrown and worked there for 2 years and then @maccosmeticsafrica for another 2 years and lastly @urbandecaycosmetics .</p>
                    <img class="img-fluid" src="portrait_Two.webp" alt="portrait_image" height="1000vh" width="680vw">
                </div>
            </div>
        </div>
    </div>
    
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
                    <div transition:scale="{{ duration: 1800, delay: 3200}}" class="col-md-4 col-sm-12">
                        <center><img class="img-fluid" src="weddings.webp" alt="portrait_image" height="800vh" width="1000vw"></center>
                        <h4>Weddings</h4>
                        <br>
                        <p>
                            <strong>MACK TWINS</strong> provide a make up experience to the bridal entourage that brings beauty and radiance on this special day of the Bride.
                        </p>
                    </div>
                    <div transition:scale="{{ duration: 2000, delay: 3300}}" class="col-md-4 col-sm-12">
                        <center><img class="img-fluid" src="portrait_Three.webp" alt="portrait_image" height="800vh" width="1000vw"></center>
                        <h4>Special Occasions</h4>
                        <br>
                        <p>
                            Your Anniversary , Your Party , Your Event , Your Special Day is where <strong>MACK TWINS</strong> bring out and ignite the beauty in YOU through makeup.
                        </p>
                    </div>
                    <div transition:scale="{{ duration: 2200, delay: 3400}}" class="col-md-4 col-sm-12">
                        <center><img class="img-fluid" src="portrait_Two.webp" alt="portrait_image" height="800vh" width="1000vw"></center>
                        <h4>Matric Balls</h4>
                        <br>
                        <p>A celebration of knowledge and beauty. This is where <strong>MACK TWINS</strong> brings out the magic of YOUR beauty to the world You are entering.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="container pb-3 pt-4">
    <div class="row">
        <div class="col-md-6 col-sm-12 pt-5 mx-auto">
            <form name='contact' method='POST' data-netlify="true">
                <fieldset>
                <div class="form-group">
                    <!-- svelte-ignore a11y-label-has-associated-control -->
                    <label>Name</label>
                    <input type="text" class="form-control" aria-describedby="emailHelp" placeholder="Enter your name" name="name">
                </div>
                <div class="form-group">
                    <!-- svelte-ignore a11y-label-has-associated-control -->
                    <label>Email address</label>
                    <input type="email" class="form-control" aria-describedby="emailHelp" placeholder="Enter your email" name="email">
                    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
                </div>
                <div class="form-group">
                    <!-- svelte-ignore a11y-label-has-associated-control -->
                    <label>Subject</label>
                    <input type="text" class="form-control" aria-describedby="emailHelp" placeholder="Enter your subject" name="subject">
                </div>
                <div class="form-group">
                    <!-- svelte-ignore a11y-label-has-associated-control -->
                    <label>Your message...</label>
                    <textarea name="message" class="form-control" id="exampleTextarea" rows="8"></textarea>
                </div>
                <center><button type="submit" class="btn btn-primary submit">Submit</button></center>
                </fieldset>
            </form>
        </div>
    </div>
</div>

<!-- Footer  -->
<footer class="footer footer_look pt-5">
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-4 col-sm-6 col-xs-12 segOne text-center">
                <p> |  Freelance Make Up Artists | GAUTENG | South Africa  | </p>
            </div>
            <div class="col-md-4 col-sm-6 col-xs-12 segmTwo text-center">
                <img class="img-fluid" src="MTME_logo.png" alt="MTME_logo" width="170" height="170">
            </div>
            <div class="col-md-3 col-sm-6 col-xs-12 segThree text-center">
                <a id="mail" href="mailtobookings@mtme.co.za" >bookings@mtme.co.za</a>
            </div>
        </div>
    </div>
</footer>
<div id="btm-border">
    <div class="container text-center">
        <a href="https://splyce.dev" target="_blank">Designed by Splyce</a>
    </div>
</div>