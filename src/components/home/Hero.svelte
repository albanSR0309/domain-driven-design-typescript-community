<style>
    .hero {
        background: var(--background-color);
        background-image: url(https://www.vibely.io/img/ico-dots.svg), url(https://www.vibely.io/img/ico-dots.svg), url(https://www.vibely.io/img/bgImg-noodleLightBlue.svg), url(https://d3lqi7z5du42f4.cloudfront.net/assets/shapes/bgImg-rightNoodle.svg), url(https://d3lqi7z5du42f4.cloudfront.net/assets/shapes/bgImg-doubleNoodle.svg), url(https://www.vibely.io/img/bgDiag.svg);
        background-repeat: no-repeat;
        background-size: 8%, 8%, 30%, 12%, 24%, contain;
        background-position: 60% 70px, 90% bottom, 0 320px, right 140px, right 520px, 0 bottom;
        padding-bottom: 2rem;
        min-height: 750px;
    }

    .information {
        flex: 1 0 60%;
    }

    .video {
        flex: 1 0 40%;
    }

    .squiggly {
        color: var(--primary-color);
        background-image: url(https://d3lqi7z5du42f4.cloudfront.net/assets/shapes/squigglyGreen2.svg);
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center bottom
    }

    .video-shape {
        background: white;
        width: 320px;
        height: 600px;
        border-radius: 18px;
    }

    .caption {
        background-image: url(https://d3lqi7z5du42f4.cloudfront.net/assets/shapes/gra-arrow.svg);
        background-repeat: no-repeat;
        padding: 2rem 0 0 0;
        background-position: 50% 0px;
    }
    @media (min-width: 590px) {
        .caption {
            padding: 2.5rem 3rem 0 43%;
            background-position: 356px 13px;
        }
    }
</style>

<section class="hero">
    <div class="wrapper flex-wrap">
        <div class="information">
            <h1>Domain-Driven Design <span class="squiggly">#typescript</span> community</h1>
            <p><span class="text-bold-secondary">Challenges</span> 👨🏼‍💻 with <span class="text-bold-primary">DDD</span>,
                <span class="text-bold-primary">code skeletons, tools, best practices, , and lasting friendships Warning</span>: extreme
                engagement & loyalty may occur.</p>
            <button class="bg-primary">Join Community</button>
            <button class="bg-base">Read more now..</button>
            <p class="caption">Discover the main contents, events and reasons to join the community. It's free.</p>
        </div>
        <div class="video">
            <div class="video-shape"></div>
        </div>
    </div>
</section>
