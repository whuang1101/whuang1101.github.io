---
title: RiseKeeper Support
permalink: /RiseKeeper/
---

# RiseKeeper Support

RiseKeeper is the alarm that makes sure you are awake, not merely that you heard it.

<style>
  .rk-showcase {
    margin: 2rem 0 2.5rem;
  }

  .rk-video-grid,
  .rk-screenshot-grid {
    display: grid;
    gap: 1rem;
  }

  .rk-video-grid {
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    margin: 1rem 0 2rem;
  }

  .rk-video-card,
  .rk-screenshot-card {
    margin: 0;
  }

  .rk-video-card video,
  .rk-screenshot-card img {
    display: block;
    width: 100%;
    height: auto;
    border: 1px solid rgba(127, 127, 127, 0.24);
    border-radius: 18px;
    background: #111;
    box-shadow: 0 10px 28px rgba(0, 0, 0, 0.16);
  }

  .rk-video-card figcaption,
  .rk-screenshot-card figcaption {
    margin-top: 0.55rem;
    color: #555;
    font-size: 0.9rem;
    text-align: center;
  }

  .rk-screenshot-grid {
    grid-template-columns: repeat(auto-fit, minmax(135px, 1fr));
    margin: 1rem 0 1.5rem;
  }

  .rk-showcase details {
    margin-top: 1rem;
  }

  .rk-showcase summary {
    cursor: pointer;
    font-weight: 600;
  }

  @media (prefers-color-scheme: dark) {
    .rk-video-card figcaption,
    .rk-screenshot-card figcaption {
      color: #aaa;
    }
  }
</style>

<section class="rk-showcase" aria-labelledby="app-previews">
  <h2 id="app-previews">App previews</h2>
  <p>See the complete RiseKeeper experience in the free app and with RiseKeeper Pro unlocked.</p>

  <div class="rk-video-grid">
    <figure class="rk-video-card">
      <video controls playsinline preload="metadata" poster="assets/showcase/6.5/list.jpg">
        <source src="assets/showcase/normal.mp4" type="video/mp4">
        <a href="assets/showcase/normal.mp4">Download the Normal preview</a>.
      </video>
      <figcaption>Normal experience</figcaption>
    </figure>

    <figure class="rk-video-card">
      <video controls playsinline preload="metadata" poster="assets/showcase/6.5/pro.jpg">
        <source src="assets/showcase/pro.mp4" type="video/mp4">
        <a href="assets/showcase/pro.mp4">Download the Pro preview</a>.
      </video>
      <figcaption>RiseKeeper Pro</figcaption>
    </figure>
  </div>

  <h2 id="screenshots">Screenshots</h2>
  <div class="rk-screenshot-grid">
    <figure class="rk-screenshot-card">
      <img src="assets/showcase/6.5/list.jpg" alt="Alarm list with upcoming alarms" loading="lazy">
      <figcaption>Alarm list</figcaption>
    </figure>
    <figure class="rk-screenshot-card">
      <img src="assets/showcase/6.5/editor.jpg" alt="Alarm editor with schedule, sound, and mission controls" loading="lazy">
      <figcaption>Alarm editor</figcaption>
    </figure>
    <figure class="rk-screenshot-card">
      <img src="assets/showcase/6.5/math.jpg" alt="Math wake-up mission" loading="lazy">
      <figcaption>Math mission</figcaption>
    </figure>
    <figure class="rk-screenshot-card">
      <img src="assets/showcase/6.5/pro.jpg" alt="RiseKeeper Pro feature page" loading="lazy">
      <figcaption>RiseKeeper Pro</figcaption>
    </figure>
    <figure class="rk-screenshot-card">
      <img src="assets/showcase/6.5/history.jpg" alt="Wake history and streak summary" loading="lazy">
      <figcaption>Wake history</figcaption>
    </figure>
    <figure class="rk-screenshot-card">
      <img src="assets/showcase/6.5/memory.jpg" alt="Memory wake-up mission with illuminated tiles" loading="lazy">
      <figcaption>Memory mission</figcaption>
    </figure>
  </div>

  <details>
    <summary>View 6.9-inch display screenshots</summary>
    <div class="rk-screenshot-grid">
      <figure class="rk-screenshot-card">
        <img src="assets/showcase/6.9/list.jpg" alt="Alarm list on a 6.9-inch display" loading="lazy">
        <figcaption>Alarm list</figcaption>
      </figure>
      <figure class="rk-screenshot-card">
        <img src="assets/showcase/6.9/editor.jpg" alt="Alarm editor on a 6.9-inch display" loading="lazy">
        <figcaption>Alarm editor</figcaption>
      </figure>
      <figure class="rk-screenshot-card">
        <img src="assets/showcase/6.9/math.jpg" alt="Math mission on a 6.9-inch display" loading="lazy">
        <figcaption>Math mission</figcaption>
      </figure>
      <figure class="rk-screenshot-card">
        <img src="assets/showcase/6.9/pro.jpg" alt="RiseKeeper Pro on a 6.9-inch display" loading="lazy">
        <figcaption>RiseKeeper Pro</figcaption>
      </figure>
      <figure class="rk-screenshot-card">
        <img src="assets/showcase/6.9/history.jpg" alt="Wake history on a 6.9-inch display" loading="lazy">
        <figcaption>Wake history</figcaption>
      </figure>
      <figure class="rk-screenshot-card">
        <img src="assets/showcase/6.9/memory.jpg" alt="Memory mission on a 6.9-inch display" loading="lazy">
        <figcaption>Memory mission</figcaption>
      </figure>
    </div>
  </details>
</section>

## Getting started

1. Allow RiseKeeper to schedule system alarms.
2. Create an alarm and choose its days, sound, snooze policy, and wake-up mission.
3. When it rings, tap **Start Mission** and complete the challenge.

## Troubleshooting

### My alarms do not appear

Open iOS Settings and make sure alarm access is enabled for RiseKeeper. Then open the app once so it can reconcile its saved alarms with AlarmKit.

### Why can the system Stop button still appear?

iOS always provides a system-controlled Stop affordance. RiseKeeper Strict Mode detects a bypass and can schedule a short re-alarm; Wake-Up Check offers an additional safeguard.

### How do I restore RiseKeeper Pro?

Open **Settings → RiseKeeper Pro → Restore Purchases**. The lifetime purchase is linked to the Apple Account used to buy it. RiseKeeper Pro is not a subscription.

### How do I change the app icon?

Open **Settings → App Icon** and choose Classic, Aurora, Obsidian, or Hyper. Classic is available to everyone; the three alternate icons are included with RiseKeeper Pro. iOS displays a confirmation after the icon changes.

## Contact

Email [risekeeper.help@outlook.com](mailto:risekeeper.help@outlook.com) for support. Include your iPhone model, iOS version, and a short description of what happened. Do not send passwords, verification codes, or other sensitive information.

- [Privacy policy](https://whuang1101.github.io/RiseKeeper/privacy/)
- [Terms of use](https://whuang1101.github.io/RiseKeeper/terms/)
- [Sound licenses](https://whuang1101.github.io/RiseKeeper/sound-licenses/)
