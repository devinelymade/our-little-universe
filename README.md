```html
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <title>For My King, Santi ❤️</title>

    <link rel="stylesheet"
          href="style.css">

</head>


<body>


<!-- =====================================================
     BACKGROUND MUSIC
===================================================== -->

<audio id="backgroundMusic" loop>

    <source
        src="I Love You Too Much.mp3"
        type="audio/mpeg">

</audio>


<!-- MUSIC BUTTON -->

<button
    id="musicButton"
    class="music-control"
    onclick="toggleMusic()"
    aria-label="Toggle music">

    🎵

</button>



<!-- =====================================================
     SECRET PADLOCK
===================================================== -->

<div id="lockScreen">

    <div class="lock-container">


        <div class="lock">

            <div class="lock-shackle"></div>

            <div class="lock-body">

                <div class="keyhole"></div>

            </div>

        </div>


        <h1 class="lock-title">
            For Santi
        </h1>


        <div class="lock-subtitle">
            A little secret from your Queen
        </div>


        <input
            id="code"
            class="code-input"
            type="password"
            inputmode="numeric"
            maxlength="6"
            placeholder="••••••"
            aria-label="Secret code"
        >


        <button
            class="unlock-button"
            onclick="unlock()">

            🔐 Unlock My Heart

        </button>


        <div id="error"></div>

    </div>

</div>



<!-- =====================================================
     HERO
===================================================== -->

<header class="hero">


    <div class="hero-small">
        A little universe made for you
    </div>


    <h1>
        My King, Santi
    </h1>


    <p>
        From your Queen, Devi ❤️
    </p>


    <!-- FLOWER CIRCLE -->

    <div class="flower-circle">


        <div class="flower"
             style="--angle:0deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="flower"
             style="--angle:45deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="flower"
             style="--angle:90deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="flower"
             style="--angle:135deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="flower"
             style="--angle:180deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="flower"
             style="--angle:225deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="flower"
             style="--angle:270deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="flower"
             style="--angle:315deg">

            <div class="flower-inner">

                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>
                <div class="petal"></div>

                <div class="flower-center"></div>

            </div>

        </div>


        <div class="center-heart">
            ❤️
        </div>

    </div>


</header>



<!-- =====================================================
     OUR STORY
===================================================== -->

<section>


    <div class="section-label">
        The beginning of us
    </div>


    <h2 class="section-title">
        Our Story
    </h2>


    <div class="story">


        <div class="story-date">
            NOVEMBER 30 · 2025
        </div>


        <p>
            The day our little story began.
        </p>


        <div class="story-heart">
            ❤️
        </div>


        <p>
            Somewhere between two countries and
            thousands of kilometers,
            two hearts found each other.
        </p>


        <br>


        <p>
            And somehow,
            you became my King
            and I became your Queen.
        </p>


        <br>


        <p>
            This is only the beginning
            of our story.
        </p>


    </div>

</section>



<!-- =====================================================
     MEMORIES
===================================================== -->

<section class="memories">


    <div class="section-label">
        Little pieces of us
    </div>


    <h2 class="section-title">
        Our Favorite Memories
    </h2>


    <p class="memory-intro">
        Every picture holds a little piece of us. ❤️
    </p>


    <div class="slider">


        <div
            class="slides"
            id="slides">


            <!-- PHOTO 1 -->

            <div class="slide">

                <div class="single-photo">

                    <img
                        src="memories/photo1.jpg"
                        alt="Our favorite memory 1">

                    <div class="memory-caption">
                        A little moment with you ❤️
                    </div>

                </div>

            </div>


            <!-- PHOTO 2 -->

            <div class="slide">

                <div class="single-photo">

                    <img
                        src="memories/photo2.jpg"
                        alt="Our favorite memory 2">

                    <div class="memory-caption">
                        One of my favorite memories 🥹
                    </div>

                </div>

            </div>


            <!-- PHOTO 3 -->

            <div class="slide">

                <div class="single-photo">

                    <img
                        src="memories/photo3.jpg"
                        alt="Our favorite memory 3">

                    <div class="memory-caption">
                        Just you and me ❤️
                    </div>

                </div>

            </div>


            <!-- PHOTO 4 -->

            <div class="slide">

                <div class="single-photo">

                    <img
                        src="memories/photo4.jpg"
                        alt="Our favorite memory 4">

                    <div class="memory-caption">
                        More memories to come ♾️
                    </div>

                </div>

            </div>


        </div>


        <button
            class="slider-button prev"
            onclick="previousSlide()">

            ‹

        </button>


        <button
            class="slider-button next"
            onclick="nextSlide()">

            ›

        </button>


    </div>


    <div
        class="dots"
        id="dots">
    </div>


</section>



<!-- =====================================================
     LOVE LETTER
===================================================== -->

<section class="letter-section">


    <div class="section-label">
        From my heart to yours
    </div>


    <h2 class="section-title">
        A Letter For You
    </h2>


    <div class="letter">


        <h3>
            To My King ❤️
        </h3>


        <p class="letter-opening">
            My Santi,
        </p>


        <p>
            I don't know if words will ever be enough
            to explain how much you mean to me,
            but I want to try.
        </p>


        <p>
            I will be the one to love you in infinity
            and beyond, to give you a home that makes
            you feel safe and loved, and to be your
            loving wife.
        </p>


        <p>
            I want to be the person you can come home to,
            the person you can laugh with,
            dream with, and grow with.
        </p>


        <p>
            Even when the distance feels big,
            I hope you remember that my heart
            has never been measured in kilometers.
        </p>


        <p>
            You are my King,
            and I am so grateful that I get
            to be your Queen.
        </p>


        <p>
            I want to make more memories with you.
            More silly moments.
            More late-night conversations.
            More adventures.
            More birthdays.
            More ordinary days that somehow
            become our favorite memories.
        </p>


        <p>
            And one day, I hope the distance between
            Argentina and the Philippines is nothing more
            than a chapter we look back on together.
        </p>


        <p>
            Until then, I will keep choosing you.
        </p>


        <p>
            I love you to infinity and beyond.
            ♾️❤️
        </p>


        <p class="signature">
            Forever your Queen,<br>
            Devi ❤️
        </p>


    </div>

</section>



<!-- =====================================================
     SPOTIFY PLAYLIST
===================================================== -->

<section class="playlist">


    <div class="section-label">
        Songs that sound like us
    </div>


    <h2 class="section-title">
        Our Playlist 🎵
    </h2>


    <p class="playlist-intro">
        Press play and let these songs tell
        a little piece of our story.
    </p>


    <div class="spotify">


        <iframe
            src="https://open.spotify.com/embed/playlist/7uC8cUciOSVzQQUgNgzA2G"
            allow="
                autoplay;
                clipboard-write;
                encrypted-media;
                fullscreen;
                picture-in-picture
            "
            loading="lazy">
        </iframe>


    </div>


    <p class="playlist-note">
        🎧 For my King, from your Queen.
    </p>


</section>



<!-- =====================================================
     FINAL SURPRISE
===================================================== -->

<section class="final">


    <div class="final-heart">
        ❤️
    </div>


    <h2>
        I Choose You
    </h2>


    <div class="infinity">
        ∞
    </div>


    <p class="final-message">


        Santi, I will love you
        in infinity and beyond.


        <br><br>


        I will love you through the distance,
        through every difficult day,
        through every beautiful moment,
        and through every chapter
        still waiting for us.


        <br><br>


        I want to give you a home
        where you feel safe,
        loved,
        understood,
        and never alone.


        <br><br>


        And someday...


        <br><br>


        I want that home to be us.


    </p>


    <div class="final-signature">

        Your loving Queen,<br>

        Devi ❤️

    </div>


    <div class="final-date">

        30 · 11 · 2025

    </div>


</section>



<!-- =====================================================
     JAVASCRIPT
===================================================== -->

<script>


/* =====================================================
   MUSIC
===================================================== */

const backgroundMusic =
    document.getElementById(
        "backgroundMusic"
    );


const musicButton =
    document.getElementById(
        "musicButton"
    );


let musicPlaying = false;


backgroundMusic.volume = 0.35;



/* START MUSIC */

function startMusic() {

    backgroundMusic
        .play()
        .then(() => {

            musicPlaying = true;

            musicButton.innerHTML = "🎵";

        })
        .catch(() => {

            musicPlaying = false;

        });

}



/* TOGGLE MUSIC */

function toggleMusic() {

    if (
        backgroundMusic.paused
    ) {

        backgroundMusic
            .play()
            .then(() => {

                musicPlaying = true;

                musicButton.innerHTML =
                    "🎵";

            });

    } else {

        backgroundMusic.pause();

        musicPlaying = false;

        musicButton.innerHTML =
            "🔇";

    }

}



/* =====================================================
   SECRET PADLOCK
===================================================== */

const secretCode =
    "113025";


function unlock() {


    const input =
        document.getElementById(
            "code"
        ).value;


    const error =
        document.getElementById(
            "error"
        );


    if (
        input === secretCode
    ) {


        document
            .getElementById(
                "lockScreen"
            )
            .classList.add(
                "unlocked"
            );


        error.innerHTML = "";


        /* Start music */

        startMusic();


        /* Celebration */

        for (
            let i = 0;
            i < 35;
            i++
        ) {

            setTimeout(
                createHeart,
                i * 70
            );

        }


    } else {


        error.innerHTML =
            "Try again, my King ❤️";


    }

}



/* ENTER KEY */

document
    .getElementById("code")
    .addEventListener(
        "keydown",
        function(event) {

            if (
                event.key === "Enter"
            ) {

                unlock();

            }

        }
    );



/* =====================================================
   MEMORY SLIDER
===================================================== */

let currentSlide = 0;


const slides =
    document.getElementById(
        "slides"
    );


const totalSlides =
    document.querySelectorAll(
        ".slide"
    ).length;


const dots =
    document.getElementById(
        "dots"
    );



/* CREATE DOTS */

for (
    let i = 0;
    i < totalSlides;
    i++
) {


    const dot =
        document.createElement(
            "div"
        );


    dot.className =
        "dot";


    dot.addEventListener(
        "click",
        function() {

            currentSlide = i;

            updateSlider();

        }
    );


    dots.appendChild(dot);

}



/* UPDATE SLIDER */

function updateSlider() {


    slides.style.transform =
        `translateX(-${currentSlide * 100}%)`;


    document
        .querySelectorAll(".dot")
        .forEach(
            (dot, index) => {

                dot.classList.toggle(
                    "active",
                    index === currentSlide
                );

            }
        );

}



/* NEXT */

function nextSlide() {


    currentSlide++;


    if (
        currentSlide >= totalSlides
    ) {

        currentSlide = 0;

    }


    updateSlider();

}



/* PREVIOUS */

function previousSlide() {


    currentSlide--;


    if (
        currentSlide < 0
    ) {

        currentSlide =
            totalSlides - 1;

    }


    updateSlider();

}


updateSlider();



/* AUTO SLIDE */

setInterval(
    nextSlide,
    5000
);



/* =====================================================
   MOBILE SWIPE
===================================================== */

let touchStartX = 0;


slides.addEventListener(
    "touchstart",
    function(event) {

        touchStartX =
            event.touches[0].clientX;

    },
    { passive: true }
);


slides.addEventListener(
    "touchend",
    function(event) {


        const touchEndX =
            event.changedTouches[0].clientX;


        const distance =
            touchStartX -
            touchEndX;


        if (
            Math.abs(distance) > 50
        ) {


            if (
                distance > 0
            ) {

                nextSlide();

            } else {

                previousSlide();

            }

        }

    },
    { passive: true }
);



/* =====================================================
   FLOATING HEARTS
===================================================== */

function createHeart() {


    const heart =
        document.createElement(
            "div"
        );


    heart.className =
        "heart";


    const symbols = [

        "❤️",
        "💕",
        "💗",
        "💖",
        "💓",
        "💞",
        "💘"

    ];


    heart.innerHTML =
        symbols[
            Math.floor(
                Math.random() *
                symbols.length
            )
        ];


    heart.style.left =
        Math.random() *
        100 +
        "vw";


    heart.style.fontSize =
        (
            12 +
            Math.random() *
            22
        ) +
        "px";


    heart.style.animationDuration =
        (
            5 +
            Math.random() *
            6
        ) +
        "s";


    document.body.appendChild(
        heart
    );


    setTimeout(
        () => heart.remove(),
        12000
    );

}



/* CONTINUOUS HEARTS */

setInterval(
    createHeart,
    1000
);



/* INITIAL HEARTS */

for (
    let i = 0;
    i < 8;
    i++
) {

    setTimeout(
        createHeart,
        i * 500
    );

}


</script>


</body>

</html>
```
