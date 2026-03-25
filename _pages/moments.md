---
layout: archive
title: "Personal Moments"
permalink: /moments/
author_profile: true
---

<style>
  .video-card {
    flex: 1;
    min-width: 300px;
    max-width: 400px;
    background: rgba(255, 255, 255, 0.7);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 20px;
    padding: 15px;
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.15);
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    text-align: center;
  }

  .video-card:hover {
    transform: translateY(-10px) scale(1.03);
    box-shadow: 0 15px 45px rgba(0, 0, 0, 0.2);
    border: 1px solid rgba(64, 158, 255, 0.5);
  }

  .video-container {
    border-radius: 15px;
    overflow: hidden;
    line-height: 0;
  }

  .video-title {
    margin-top: 15px;
    font-size: 1.1em;
    font-weight: 600;
    background: linear-gradient(45deg, #2c3e50, #4ca1af);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
</style>

Welcome to my personal corner! 🎸 🎮

<div style="display: flex; flex-wrap: wrap; gap: 30px; justify-content: center; margin-top: 40px; padding: 10px;">

  <div class="video-card">
    <div class="video-container">
      <video width="100%" controls poster="https://via.placeholder.com/400x225/f0f0f0/666666?text=Academic+Life">
          <source src="{{ '/assets/videos/book.mp4' | relative_url }}" type="video/mp4">
      </video>
    </div>
    <div class="video-title">📚 Academic Life</div>
  </div>

  <div class="video-card">
    <div class="video-container">
      <video width="100%" controls poster="https://via.placeholder.com/400x225/f0f0f0/666666?text=Creative+Fun">
          <source src="{{ '/assets/videos/fun.mp4' | relative_url }}" type="video/mp4">
      </video>
    </div>
    <div class="video-title">🎬 Creative Fun</div>
  </div>

  <div class="video-card">
    <div class="video-container">
      <video width="100%" controls poster="https://via.placeholder.com/400x225/f0f0f0/666666?text=Exploration">
          <source src="{{ '/assets/videos/mountain.mp4' | relative_url }}" type="video/mp4">
      </video>
    </div>
    <div class="video-title">⛰️ Travel & Exploration</div>
  </div>

</div>

---
<p style="text-align: center; font-style: italic; color: #888;">"Stay hungry, stay foolish."</p>