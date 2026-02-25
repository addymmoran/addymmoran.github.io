---
layout: default
title: Stats Study Guide
---

<script src="https://cdnjs.cloudflare.com/ajax/libs/openseadragon/4.1.0/openseadragon.min.min.js"></script>

<div id="openseadragon1" style="width: 100%; height: 600px; background: #111; border-radius: 8px;"></div>

<script type="text/javascript">
    var viewer = OpenSeadragon({
        id: "openseadragon1",
        prefixUrl: "https://cdnjs.cloudflare.com/ajax/libs/openseadragon/4.1.0/images/",
        tileSources: {
            type: 'image',
            url:  'https://addymmoran.github.io/images/StatsStudyGuide.jpeg'
        },
        showNavigator:  true,
        zoomPerScroll: 2
    });
</script>