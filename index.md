---
layout: landing
---

<section class="ld-hero">
  <div class="ld-hero-text">
    <div class="ds-hero">
      <img src="{{ site.baseurl }}/images/logo.png" alt="DOPE Sync logo">
      <div>
        <div class="ds-word">DOPE <span class="sync">SYNC</span></div>
        <div class="ds-tag">BALLISTIC DOPE ON GARMIN</div>
      </div>
    </div>
    <h1 class="ld-title">Your range card, on your wrist.</h1>
    <p class="ld-lead">Build your card in GeoBallistics or Applied Ballistics like you already do, share it, and it's on your Garmin watch. No retyping, no tape on the stock, no phone out on the line.</p>
    <div class="ld-ctas">
      <a class="ld-btn ld-btn-primary" href="mailto:taylor@taylormadetech.io?subject=DopeSync%20beta">Join the beta</a>
      <a class="ld-btn" href="{{ site.baseurl }}/user-guide/">User guide</a>
    </div>
    <p class="ld-small">Android beta now. iPhone in testing. Never calculates ballistics: it shows exactly what your solver produced.</p>
  </div>
  <figure class="ld-hero-media">
    <video src="{{ site.baseurl }}/images/dopesync-demo.mp4" poster="{{ site.baseurl }}/images/watch-gb-card.png" autoplay muted loop playsinline></video>
    <figcaption>A card arrives, the watch buzzes, you press <strong>Launch</strong>.</figcaption>
  </figure>
</section>

<section class="ld-section" id="how">
  <h2>How it works</h2>
  <div class="ld-steps">
    <div class="ld-card"><span class="ld-num">1</span><h3>Build your card</h3><p>In GeoBallistics (Comp or Chart) or Applied Ballistics, the same way you do today.</p></div>
    <div class="ld-card"><span class="ld-num">2</span><h3>Share to DopeSync</h3><p>Export as CSV and pick DopeSync in the share menu. You can go right back to what you were doing.</p></div>
    <div class="ld-card"><span class="ld-num">3</span><h3>Read it on your wrist</h3><p>Every target's range, elevation and wind, big and readable in sun.</p></div>
  </div>
</section>

<section class="ld-section" id="sync">
  <h2>Watch it sync</h2>
  <p class="ld-sub">Real phone recordings (sped up 1.5x) next to the watch, with the same card on both.</p>
  <div class="ld-videos">
    <figure>
      <video src="{{ site.baseurl }}/images/dopesync-gb-chart.mp4" poster="{{ site.baseurl }}/images/dopesync-gb-chart-poster.jpg" controls muted playsinline preload="none"></video>
      <figcaption><strong>GeoBallistics Chart</strong><br>Full 100 to 1,000 yd table</figcaption>
    </figure>
    <figure>
      <video src="{{ site.baseurl }}/images/dopesync-gb-comp.mp4" poster="{{ site.baseurl }}/images/dopesync-gb-comp-poster.jpg" controls muted playsinline preload="none"></video>
      <figcaption><strong>GeoBallistics Comp</strong><br>4-target stage card</figcaption>
    </figure>
    <figure>
      <video src="{{ site.baseurl }}/images/dopesync-ab.mp4" poster="{{ site.baseurl }}/images/dopesync-ab-poster.jpg" controls muted playsinline preload="none"></video>
      <figcaption><strong>Applied Ballistics</strong><br>Lettered targets, two winds*</figcaption>
    </figure>
  </div>
  <p class="ld-small">Phone: real recording. Watch: the Connect IQ simulator showing the same card, timed to when it arrived.<br>
  * Rows D and E show <code>--</code> because this recording used Applied Ballistics' free version, which doesn't solve past its range limit. A paid AB plan fills them in.</p>
</section>

<section class="ld-section ld-split" id="features">
  <div>
    <h2>On the watch</h2>
    <ul class="ld-features">
      <li><strong>Every target on one screen.</strong> Long cards page with Up/Down.</li>
      <li><strong>Colored direction letters</strong> (U/D, L/R) so you dial the right way.</li>
      <li><strong>Wind as a clock position</strong> relative to your shot: 22 MPH @ 6:00.</li>
      <li><strong>Two-wind ranges</strong> for Applied Ballistics: R 0.2-0.3.</li>
      <li><strong>Stage card + 5 pins.</strong> Each share replaces the stage card; your 100-yard profile and 22LR stay pinned.</li>
      <li><strong>Tactical mode:</strong> black and red only. Hold Start to switch.</li>
    </ul>
  </div>
  <div>
    <div class="ld-mode" role="group" aria-label="Watch display mode">
      <button type="button" class="ld-mode-btn is-on" data-mode="std" aria-pressed="true">Standard</button>
      <button type="button" class="ld-mode-btn" data-mode="tac" aria-pressed="false">Tactical</button>
    </div>
    <div class="ld-shots">
      <figure><img class="ld-swap" src="{{ site.baseurl }}/images/watch-gb-card.png"
                   data-std="{{ site.baseurl }}/images/watch-gb-card.png"
                   data-tac="{{ site.baseurl }}/images/watch-gb-card-tactical.png" alt="GeoBallistics stage card"><figcaption><strong>GeoBallistics</strong> stage card</figcaption></figure>
      <figure><img class="ld-swap" src="{{ site.baseurl }}/images/watch-ab-card.png"
                   data-std="{{ site.baseurl }}/images/watch-ab-card.png"
                   data-tac="{{ site.baseurl }}/images/watch-ab-card-tactical.png" alt="Applied Ballistics two-wind card"><figcaption><strong>Applied Ballistics</strong>, two winds</figcaption></figure>
    </div>
    <p class="ld-small ld-mode-note">Tactical mode: hold Start on the watch.</p>
  </div>
</section>

<section class="ld-section" id="works">
  <h2>Works with</h2>
  <div class="ld-steps">
    <div class="ld-card"><h3>Ballistic apps</h3><p>GeoBallistics (Comp and Chart exports) and Applied Ballistics (stage exports).</p></div>
    <div class="ld-card"><h3>Phones</h3><p>Android (beta). iPhone in testing.</p></div>
    <div class="ld-card"><h3>Watches</h3><p>fenix 5 Plus, 6, 7, 8, 9 and E, epix, Enduro, MARQ, Forerunner 245 to 970.</p></div>
  </div>
</section>

<section class="ld-section ld-end">
  <p>Questions or feedback: <a href="mailto:taylor@taylormadetech.io">taylor@taylormadetech.io</a></p>
  <p class="ld-small">DOPE Sync is not affiliated with or endorsed by GeoBallistics, Applied Ballistics or Garmin.</p>
</section>

<script>
  // Standard / Tactical switch for the watch screenshots.
  (function () {
    var buttons = document.querySelectorAll('.ld-mode-btn');
    var imgs = document.querySelectorAll('.ld-swap');
    imgs.forEach(function (img) { new Image().src = img.dataset.tac; });
    buttons.forEach(function (b) {
      b.addEventListener('click', function () {
        buttons.forEach(function (x) {
          var on = x === b;
          x.classList.toggle('is-on', on);
          x.setAttribute('aria-pressed', on ? 'true' : 'false');
        });
        imgs.forEach(function (img) { img.src = img.dataset[b.dataset.mode]; });
      });
    });
  })();
</script>
