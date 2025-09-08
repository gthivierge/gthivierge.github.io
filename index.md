---
# This front matter makes Jekyll process SCSS. Keep it at the top!
---

@import "alembic"; // load the theme's CSS first

/* Your overrides */
.about-wrap {
  max-width: 900px;
  margin: 0 auto 3rem;
  padding: 0 1rem;
  display: flex;
  gap: 2rem;
  align-items: flex-start;
}

.about-text { flex: 1 1 60%; }

.about-photo { flex: 0 0 auto; }

.about-photo img {
  width: 220px;
  height: 220px;
  border-radius: 50%;
  object-fit: cover;
  display: block;
}

/* Mobile stacking */
@media (max-width: 800px) {
  .about-wrap {
    flex-direction: column-reverse;
    align-items: center;
  }
}

---
title: About me
layout: default
---

<div class="about-wrap">
  <div class="about-text">
    <h2>Hello!</h2>
    <p>I’m Gabrielle.</p>
    <p>I am a 5th year PhD candidate in the department of statistis and data science at Carnegie Mellon University. I am advised by Will Townes and am part of the [Delphi group](https://delphi.cmu.edu/). I plan to graduate in May 2026 and am currently seeking industry positions. I have previous experience in both the pharmaceutical industry and fixed income investments, and am always excited to learn new subject matter through the lens of statistics. </p>
  </div>

  <div class="about-photo">
    <img src="{{ '/assets/images/headshot.jpg' | relative_url }}" alt="GT headshot">
  </div>
</div>



