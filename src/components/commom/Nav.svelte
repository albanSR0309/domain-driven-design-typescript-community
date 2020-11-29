<script>
    import GithubIcon from "../svg/GithubIcon.svelte";
    export let segment;
</script>

<style>
    a {
        display: flex;
        align-items: center;
        text-decoration: none;
    }

    .header {
        position: sticky;
        top: 0;
        font-weight: 300;
        background: #e4fcfc;
        background: rgb(228 252 252 / 47%);
        backdrop-filter: blur(6px);
        font-size: 0.95rem;
    }

    .wrapper--xl {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 60px;
    }

    .brand-logo {
        width: 40px;
        border-radius: 14px;
    }

    .navbar {
        display: flex;
        align-items: center;
    }
    .navbar-button {
        display: none;
        padding: 0.7rem 1rem;
        font-size: 1rem;
        margin-left: 1rem;
    }
    @media (min-width: 690px) {
        .navbar-button {
            display: inherit;
        }
    }

    /*[aria-current] {*/
    /*    position: relative;*/
    /*    display: inline-block;*/
    /*}*/

    /*[aria-current]::after {*/
    /*    position: absolute;*/
    /*    content: '';*/
    /*    width: calc(100% - 1em);*/
    /*    height: 2px;*/
    /*    display: block;*/
    /*    bottom: -1px;*/
    /*}*/

</style>

<header class="header">
    <div class="wrapper--xl">
        <div class="brand">
            <a aria-current="{segment === undefined ? 'page' : undefined}" href="../../..">
                <img src="logo.jpg" alt="Brand" class="brand-logo">
            </a>
        </div>
        <nav class="navbar">
            <a href="">
                View on Github <GithubIcon />
            </a>
            <a aria-current="{segment === undefined ? 'page' : undefined}" href="../../..">
                <button class="navbar-button bg-primary">Join the community</button>
            </a>
        </nav>
        <!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
             the blog data when we hover over the link or tap it on a touchscreen -->
        <!--		<li><a rel=prefetch aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">blog</a></li>-->
    </div>
</header>


