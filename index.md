---
layout: index
title: 'Spring Loaded Double Pantograph'
subtitle: 'A Spring Loaded Double Pantograph (SLDP) mechanism is presented for safe balance training in elderly individuals practicing Tai Chi exercises. As people age, maintaining balance becomes increasingly critical, yet fear of falling often prevents effective exercise, creating a counterproductive cycle that increases fall risk. This natural hesitation to push physical limits during solo practice highlights the need for reliable safety systems.  This paper presents a mechanism that provides variable assistance through spring-loaded actuation, so that support and freedom of movement can be balanced in a way that is both effective and unobtrusive. Here, it will be shown that, although support and unrestricted movement are traditionally considered contradictory goals, the two can be achieved simultaneously through mechanical design and the level of assistance can be automatically regulated. In this system, the support mechanism can a) detect falls rapidly, b) provide up to 98 % body weight support when needed, and c) remain imperceptible during normal exercise.'
---

<script>
document.addEventListener('DOMContentLoaded', function() {
    const video = document.getElementById('autoplayVideo');
    // Try to play video after page loads
    video.play().catch(function(error) {
        console.log("Video autoplay failed:", error);
    });
});
</script>


     
<script src="https://vjs.zencdn.net/8.0.4/video.min.js"></script>

<center>
    <img src="/user-results/vealy_vid.gif" 
     style="
        display: block;
        width: 50%;
        max-width: 300px;
        height: auto;
        margin: 0 auto;
        border: 1px solid rgba(0,0,0,0.1);
        border-radius: 12px;
        background: white;
        box-shadow: 0 4px 6px rgba(0,0,0,0.05);"
     alt="Demo">
</center>
<span style="font-size:medium;">
    A test participant demonstrating controlled Tai Chi movements and simulated falls. The SLDP physical prototype is seen supporting the participants during the falls and imbalance. For detailed interactions and comprehensive results from all user trials, visit <a href="{{ item.url | relative_url }}/user-sessions">user sessions</a> page.</span>

<center style="margin-top:2em;margin-bottom:2em">
    <img src="/figures/kinematic_nomenclature.png" style="width:50%;"/>
    <span style="font-size:medium;">
    Schematic Diagram of SLDP</span>
</center>



## Tai Chi Movements
Our practitoners from Harvard Medical School demonstrated traditional Tai Chi movements which provided valuable insights into natural human motion patterns, particularly focusing on balance, coordination, and range of motion. These observations informed our system design and guided the development of the SLDP mechanism which aims to replicate the fluid and controlled nature of Tai Chi movements. See <a href="{{ item.url | relative_url }}/tai-chi">tai chi movements</a> for entire interaction.


## Design

<!--#### Evaluating solvers on a set of static poses-->
<br/><br/>
<center>
    <img src="/figures/cad_ss.png" style="width:25%;"/>
</center>
<span style="font-size:medium;">
Computer-aided design (CAD) model showing the SLDP system with support structure, mechanical linkages, and instrumentation placements. The model illustrates key components including the double-pantograph mechanism, spring loading system, and sensor locations. See <a href="{{ item.url | relative_url }}/design">full design</a> for complete model.</span>

## Fabrication

<!--#### Evaluating solvers on a set of static poses-->
<br/><br/>
<center>
    <img src="/figures/annonanted_physical_system_1.jpeg" style="width:25%;"/>
</center>
<span style="font-size:medium;">
Physical implementation of the SLDP mechanism showing a user testing the system. Mechanical components and sensing instrumentation are annotated. See <a href="{{ item.url | relative_url }}/fabrication">fabrication</a> for complete construction process.</span>


## Results

We evaluated the performance of the SLDP mechanism in the physical system through experimental trials with 13 users (See <a href="{{ item.url | relative_url }}/user-sessions">results for all user sessions</a>), analyzing its performance against our three system objectives:
- Maintaining natural movement patterns by allowing unrestricted motion in 3D space
- Providing adaptive assistance based on user needs
- Ensuring rapid fall detection and prevention

<table style="width: 100%; border-collapse: collapse; margin: 30px 0;">
  <tr>
    <td style="width: 33%; padding: 10px; vertical-align: top; text-align: center;">
      <img src="/figures/experiemental_workspace.png" alt="Experimental workspace volume" style="width: 100%; border: 1px solid #eee;">
      <p style="font-size: 14px; margin-top: 10px; line-height: 1.4;">Experimental workspace volume across all user trials.</p>
    </td>
    
    <td style="width: 33%; padding: 10px; vertical-align: top; text-align: center;">
      <img src="/figures/metric_subplots.png" alt="Metric subplots" style="width: 100%; border: 1px solid #eee;">
      <p style="font-size: 14px; margin-top: 10px; line-height: 1.4;">Scatter plots of the different users' weight to peak force and max fall distance.</p>
    </td>
    
    <td style="width: 33%; padding: 10px; vertical-align: top; text-align: center;">
      <img src="/figures/conf_matrix.png" alt="Confusion matrix" style="width: 100%; border: 1px solid #eee;">
      <p style="font-size: 14px; margin-top: 10px; line-height: 1.4;">Confusion matrix of the fall detection abilities of the system.</p>
    </td>
  </tr>
</table>

