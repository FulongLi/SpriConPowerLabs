---
layout: default
title: Home
description: AI-assisted power electronics converter design automation.
---

<header class="hero">
  <!-- Video hero (disabled — use image below)
  <video class="hero-video" autoplay muted loop playsinline>
    <source src="{{ '/images/vids/main.mp4' | relative_url }}" type="video/mp4">
  </video>
  -->
  <img class="hero-video" src="{{ '/images/background/home.png' | relative_url }}" alt="DC microgrid illustration">
  <div class="bg"></div>
  <div class="container">
    <span class="badge" style="color: #fff;">AI-Assisted Design Automation</span>
    <h1 style="color: #fff;">Faster, smarter design — from device to system</h1>
    <p class="lead" style="color: #fff;">
      We accelerate power-electronics development with AI: automated topology exploration,
      magnetics sizing, loss & thermal modeling, and control synthesis — validated by rigorous
      test workflows.
    </p>
    <div class="hero-actions">
      <a class="btn btn-primary" href="{{ '/contact/' | relative_url }}">Request a demo</a>
      <a class="btn btn-ghost" href="{{ '/research/services/' | relative_url }}">See capabilities</a>
    </div>
  </div>
</header>

<section class="section">
  <div class="container">
    <h2>Our Services</h2>
    <div class="grid">
      <div class="card" style="text-align:center;">
        <img src="{{ '/images/research/microgrids.png' | relative_url }}" alt="Microgrids" style="width:100%;max-width:240px;border:1px solid #ccc;border-radius:6px;margin-bottom:1rem;">
        <h3>Microgrids</h3>
        <p>Designing, modeling, and controlling DC and AC microgrids for resilient and efficient energy distribution.
           Expertise in hybrid AC/DC architectures and renewable integration.</p>
        <a href="{{ '/research/microgrids/' | relative_url }}" style="display:inline-block;margin-top:1rem;color:var(--brand);font-weight:600;text-decoration:none;">Learn More →</a>
      </div>
      <div class="card" style="text-align:center;">
        <img src="{{ '/images/research/converter.png' | relative_url }}" alt="Converters" style="width:100%;max-width:240px;border:1px solid #ccc;border-radius:6px;margin-bottom:1rem;">
        <h3>Converters</h3>
        <p>Optimized converter design and control strategies for high-performance applications — buck/boost, LLC, DAB,
           multi-level DC-AC — with automated parameter search and soft-switching control regions.</p>
        <a href="{{ '/research/converters/' | relative_url }}" style="display:inline-block;margin-top:1rem;color:var(--brand);font-weight:600;text-decoration:none;">Learn More →</a>
      </div>
      <div class="card" style="text-align:center;">
        <img src="{{ '/images/research/components.png' | relative_url }}" alt="Components" style="width:100%;max-width:240px;border:1px solid #ccc;border-radius:6px;margin-bottom:1rem;">
        <h3>Components</h3>
        <p>Deep knowledge of modern semiconductor devices (SiC/GaN) and passive components, enabling efficient, reliable,
           and compact solutions tailored to your thermal and cost constraints.</p>
        <a href="{{ '/research/devices/' | relative_url }}" style="display:inline-block;margin-top:1rem;color:var(--brand);font-weight:600;text-decoration:none;">Learn More →</a>
      </div>
    </div>
  </div>
</section>



<section class="section">
  <div class="container">
    <h2>What our automation does</h2>
    <p class="lead">A modular toolchain that plugs into your design flow — or we run it for you as a service.</p>
    <div class="grid">
      <div class="card"><h3>Topology exploration</h3><p>LLC, DAB, multi-level DC-AC, interleaved buck/boost — with constraint-aware screening.</p></div>
      <div class="card"><h3>Magnetics & devices</h3><p>Core selection, winding windows, copper loss; WBG device picking with switching-loss estimates.</p></div>
      <div class="card"><h3>Loss & thermal models</h3><p>Datasheet + surrogate models produce efficiency maps and thermal limits over the mission profile.</p></div>
      <div class="card"><h3>Control synthesis</h3><p>Phase-shift/TPWM strategies, current/voltage loops, soft-switching regions — tuned automatically.</p></div>
      <div class="card"><h3>Multi-objective optimization</h3><p>η, density, cost, temperature, EMI headroom — Pareto trade-offs with clear design rationales.</p></div>
      <div class="card"><h3>Validation planning</h3><p>Generates test matrices, HIL/SIL hooks, and data capture scripts for repeatable experiments.</p></div>
    </div>
  </div>
</section>
