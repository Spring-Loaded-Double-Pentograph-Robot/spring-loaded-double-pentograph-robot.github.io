---
permalink: /sessions/emulated-therapy-session/
title: Emulated Therapy Session
subtitle: "In the emulated therapy, 'shoulder flexion with elbow extension therapy', we program the robot to follow a trajectory that guides the user's forearm to rotate around his elbow joint. The metrics evaluated for every solver is presented here."
---

<script src="https://vjs.zencdn.net/8.0.4/video.min.js"></script>


## Third person view

<div style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%">
<video class="video-js" style="display:block;width:100%;height:fit-content;" controls preload="auto">
  <source src="/system-videos/third-person.webm" type="video/webm">
</video>
</div>

## First person view

<div style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%">
<video class="video-js" style="display:block;width:100%;height:fit-content;" controls preload="auto">
  <source src="/system-videos/first-person.webm" type="video/webm">
</video>
</div>

## Reconstructed views for different solvers
We rendered these views in simulation to compute overlay ratio, an intuitive metric to measure
the quality of alignment produced by alignment solvers. We define the overlay ratio of a frame as the proportion of the robot covered by the projected avatar
as seen from the user. With these videos, the overlay ratios can be computed as the green area divided by the red and green area combined.

<table style="table-layout:fixed;width:100%;">
    <tr><th style="width:33.333%">ONIA (ours)</th><th style="width:33.333%">Jacobian</th><th style="width:33.333%">FABRIK</th></tr>
    <tr>
        <td>
        <video class="video-js" style="display:block;width:100%;height:fit-content;" controls preload="auto">
        <source src="/system-videos/solver-onia.webm" type="video/webm">
        </video>
        </td>
        <td>
        <video class="video-js" style="display:block;width:100%;height:fit-content;" controls preload="auto">
        <source src="/system-videos/solver-onia.webm" type="video/webm">
        </video>
        </td>
        <td>
        <video class="video-js" style="display:block;width:100%;height:fit-content;" controls preload="auto">
        <source src="/system-videos/solver-onia.webm" type="video/webm">
        </video>
        </td>
    </tr>
</table>

## Metrics
We give interactive plots of all six metrics here. Hover over the traces to see the exact values.

<div id="plot-overlay-ratio" style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%;height:400px;"></div>
<div id="plot-elbow-dev" style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%;height:400px;"></div>
<div id="plot-wrist-dev" style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%;height:400px;"></div>
<div id="plot-fore-scaling" style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%;height:400px;"></div>
<div id="plot-upper-scaling" style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%;height:400px;"></div>
<div id="plot-run-time" style="margin-left:auto;margin-right:auto;margin-top:20px;max-width:60%;height:400px;"></div>