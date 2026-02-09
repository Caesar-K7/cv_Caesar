ni kodeya

css

.hero-image img {
    width: 320px;
    height: auto;
    -webkit-mask-image:
        linear-gradient(to left, transparent, black 45%),
        linear-gradient(to bottom, transparent, black 25%);
    -webkit-mask-composite: intersect;
    mask-image:
        linear-gradient(to left, transparent, black 45%),
        linear-gradient(to bottom, transparent, black 25%);
    mask-composite: intersect;
    filter: drop-shadow(0 0 25px rgba(0,0,0,0.35));
}

html

<div class="hero-image">
            <img src="IMG-20260209-WA0000.jpg" alt="Foto Caesar">
        </div>
