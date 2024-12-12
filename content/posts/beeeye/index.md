---
title: "BeeEye"
date: 2024-03-11
summary: "A WebGL filter that simulates bee vision"
tags: ["WebGL", "Filter"]
---

A real-time filter that simulates how bees see the world, with both image and webcam support.

<style>
    /* Override PaperMod's container width */
    .post-content {
        max-width: none !important;
        width: 100% !important;
        padding: 0 !important;
    }
    
    /* Ensure our container takes full width */
    .filter-container {
        width: 100vw !important;
        position: relative !important;
        left: 50% !important;
        right: 50% !important;
        margin-left: -50vw !important;
        margin-right: -50vw !important;
        padding: 20px !important;
        overflow: visible !important;
    }
    
    /* Style the iframe */
    .filter-iframe {
        width: 100% !important;
        height: 1500px !important;
        border: none !important;
        border-radius: 8px !important;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1) !important;
        display: block !important;
        margin: 0 auto !important;
        max-width: 1400px !important; /* Reasonable max-width for very wide screens */
    }
</style>

<div class="filter-container">
    <iframe 
        src="/beeeye/filter.html" 
        class="filter-iframe"
        allow="camera"
        allowfullscreen
        scrolling="no"
    ></iframe>
</div>
