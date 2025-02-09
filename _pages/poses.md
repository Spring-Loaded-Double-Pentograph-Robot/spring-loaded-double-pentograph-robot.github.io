---
permalink: /poses/
title: Poses
subtitle: 'We evaluated the performance of the three solvers through a set of 12 static poses. Poses are chosen in group, with each group representative of one partition of the space of all possible robot arm poses. Poses 1 to 3 covers the general case of hands up, and vary in whether the hand points forward, upright, or backward; Likewise, poses 9 to 11 covers the case of hands down; Poses 5 to 8 covers different cases where the arms are in front of the body; Poses 4 and 12 are the standard T-pose and A-pose. '
---

## All poses overview
<img src="/images/poses/all-poses.png" style="max-width:60%">

Metrics:
<img src="/images/poses/poses-metrics.png" style="max-width:60%">

## Pose 1

**Description**: upper arms to the side and parallel to the ground; forearms and hands pointing down to the ground and 
a bit to the front, forming a right angle with the upper arms. (barely natural for humans) 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/0.jpg"></td>
    <td><img src="/images/poses/jacobian/0.jpg"></td>
    <td><img src="/images/poses/fabrik/0.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.766365</b></td><td>0.539608</td><td>0.666389</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>3.8743e-07</b></td><td>0.0293432</td><td>0.0425887</td></tr>
    <tr><td>Right</td><td><b>3.50098e-07</b></td><td>0.0316151</td><td>0.0440972</td></tr>
    <tr><td>Avg.</td><td><b>3.68764e-07</b></td><td>0.0304792</td><td>0.0433429</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>2.98396e-07</b></td><td>0.119434</td><td>0.0987662</td></tr>
    <tr><td>Right</td><td><b>1.9992e-07</b></td><td>0.105549</td><td>0.080948</td></tr>
    <tr><td>Avg.</td><td><b>2.49158e-07</b></td><td>0.112491</td><td>0.0898571</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>0.857055</td><td>0.80781</td><td><b>0.881984</b></td></tr>
    <tr><td>Right</td><td>0.911098</td><td>0.854293</td><td><b>0.921574</b></td></tr>
    <tr><td>Avg.</td><td>0.884077</td><td>0.831051</td><td><b>0.901779</b></td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.35283</td><td><b>1.13382</b></td><td>1.3</td></tr>
    <tr><td>Right</td><td>1.32345</td><td><b>1.14823</b></td><td>1.3</td></tr>
    <tr><td>Avg.</td><td>1.33814</td><td><b>1.14103</b></td><td>1.3</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0108</b></td><td>0.0864</td><td>0.3354</td></tr>
    <tr><td>Right</td><td><b>0.0073</b></td><td>0.0405</td><td>0.3205</td></tr>
    <tr><td>Avg.</td><td><b>0.00905</b></td><td>0.06345</td><td>0.32795</td></tr>
</table>
    

## Pose 2

**Description**: upper arms to the side and parallel to the ground; forearms and hands pointing straight down to the 
ground, forming a right angle with the upper arms. (unnatural for humans) 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/1.jpg"></td>
    <td><img src="/images/poses/jacobian/1.jpg"></td>
    <td><img src="/images/poses/fabrik/1.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.799706</b></td><td>0.44196</td><td>0.550578</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>5.03121e-07</b></td><td>0.0264918</td><td>0.127784</td></tr>
    <tr><td>Right</td><td><b>3.39799e-07</b></td><td>0.0316821</td><td>0.150004</td></tr>
    <tr><td>Avg.</td><td><b>4.2146e-07</b></td><td>0.029087</td><td>0.138894</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>9.42432e-08</b></td><td>0.177354</td><td>0.201369</td></tr>
    <tr><td>Right</td><td><b>1.61181e-07</b></td><td>0.177615</td><td>0.191593</td></tr>
    <tr><td>Avg.</td><td><b>1.27712e-07</b></td><td>0.177485</td><td>0.196481</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>0.856306</td><td>0.707283</td><td><b>0.934562</b></td></tr>
    <tr><td>Right</td><td>0.908608</td><td>0.751991</td><td><b>0.979059</b></td></tr>
    <tr><td>Avg.</td><td>0.882457</td><td>0.729637</td><td><b>0.956811</b></td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.34307</td><td><b>0.975567</b></td><td>1.3</td></tr>
    <tr><td>Right</td><td>1.32904</td><td><b>0.968398</b></td><td>1.3</td></tr>
    <tr><td>Avg.</td><td>1.33606</td><td><b>0.971982</b></td><td>1.3</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0113</b></td><td>0.0731</td><td>0.3408</td></tr>
    <tr><td>Right</td><td><b>0.0074</b></td><td>0.0381</td><td>0.3235</td></tr>
    <tr><td>Avg.</td><td><b>0.00935</b></td><td>0.0556</td><td>0.33215</td></tr>
</table>
    

## Pose 3

**Description**: upper arms to the side and parallel to the ground; forearms and hands pointing down to the ground and
a bit to the back, forming a right angle with the upper arms. (unnatural for humans) 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/2.jpg"></td>
    <td><img src="/images/poses/jacobian/2.jpg"></td>
    <td><img src="/images/poses/fabrik/2.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.819356</b></td><td>0.45772</td><td>0.475702</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>1.93141e-07</b></td><td>0.0208567</td><td>0.104221</td></tr>
    <tr><td>Right</td><td><b>4.15098e-07</b></td><td>0.0251126</td><td>0.116726</td></tr>
    <tr><td>Avg.</td><td><b>3.0412e-07</b></td><td>0.0229847</td><td>0.110473</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.90828e-07</b></td><td>0.191344</td><td>0.165518</td></tr>
    <tr><td>Right</td><td><b>1.36571e-07</b></td><td>0.197644</td><td>0.182101</td></tr>
    <tr><td>Avg.</td><td><b>1.637e-07</b></td><td>0.194494</td><td>0.17381</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td><b>0.844692</b></td><td>0.7</td><td>0.7</td></tr>
    <tr><td>Right</td><td><b>0.904684</b></td><td>0.7</td><td>0.7</td></tr>
    <tr><td>Avg.</td><td><b>0.874688</b></td><td>0.7</td><td>0.7</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.33006</td><td><b>0.94176</b></td><td>1.3</td></tr>
    <tr><td>Right</td><td>1.32373</td><td><b>0.939586</b></td><td>1.3</td></tr>
    <tr><td>Avg.</td><td>1.3269</td><td><b>0.940673</b></td><td>1.3</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0108</b></td><td>0.0704</td><td>0.3342</td></tr>
    <tr><td>Right</td><td><b>0.0072</b></td><td>0.0399</td><td>0.3837</td></tr>
    <tr><td>Avg.</td><td><b>0.009</b></td><td>0.05515</td><td>0.35895</td></tr>
</table>
    

## Pose 4

**Description**: upper arms to the side and parallel to the ground; forearms and hands pointing up and
a bit to the front, forming a right angle with the upper arms. 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/3.jpg"></td>
    <td><img src="/images/poses/jacobian/3.jpg"></td>
    <td><img src="/images/poses/fabrik/3.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td>0.760668</td><td>0.764318</td><td><b>0.773317</b></td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>4.10864e-07</b></td><td>0.00317555</td><td>0.000419434</td></tr>
    <tr><td>Right</td><td><b>1.3411e-07</b></td><td>0.000802382</td><td>0.00028065</td></tr>
    <tr><td>Avg.</td><td><b>2.72487e-07</b></td><td>0.00198897</td><td>0.000350042</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.46001e-07</b></td><td>0.0125198</td><td>0.0154571</td></tr>
    <tr><td>Right</td><td><b>4.21468e-08</b></td><td>0.0029745</td><td>0.00375389</td></tr>
    <tr><td>Avg.</td><td><b>9.40739e-08</b></td><td>0.00774715</td><td>0.00960552</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>0.876265</td><td>0.879465</td><td><b>0.88072</b></td></tr>
    <tr><td>Right</td><td>0.92602</td><td><b>0.926201</b></td><td>0.926184</td></tr>
    <tr><td>Avg.</td><td>0.901143</td><td>0.902833</td><td><b>0.903452</b></td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.36326</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td>Right</td><td>1.3145</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td>Avg.</td><td>1.33888</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0122</b></td><td>0.1132</td><td>0.1691</td></tr>
    <tr><td>Right</td><td><b>0.0087</b></td><td>0.0427</td><td>0.1082</td></tr>
    <tr><td>Avg.</td><td><b>0.01045</b></td><td>0.07795</td><td>0.13865</td></tr>
</table>
    

## Pose 5

**Description**: upper arms to the side and parallel to the ground; forearms and hands pointing straight up and
, forming a right angle with the upper arms. 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/4.jpg"></td>
    <td><img src="/images/poses/jacobian/4.jpg"></td>
    <td><img src="/images/poses/fabrik/4.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td>0.800069</td><td>0.800757</td><td><b>0.810365</b></td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>1.9992e-07</b></td><td>0.0030345</td><td>0.000676116</td></tr>
    <tr><td>Right</td><td><b>3.05383e-07</b></td><td>0.000148244</td><td>0.000504133</td></tr>
    <tr><td>Avg.</td><td><b>2.52651e-07</b></td><td>0.00159137</td><td>0.000590124</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.49012e-07</b></td><td>0.0120602</td><td>0.0148265</td></tr>
    <tr><td>Right</td><td><b>1.36571e-07</b></td><td>0.00241702</td><td>0.000230632</td></tr>
    <tr><td>Avg.</td><td><b>1.42792e-07</b></td><td>0.00723861</td><td>0.00752856</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>0.874065</td><td><b>0.878981</b></td><td>0.876564</td></tr>
    <tr><td>Right</td><td>0.913246</td><td><b>0.913566</b></td><td>0.913197</td></tr>
    <tr><td>Avg.</td><td>0.893655</td><td><b>0.896274</b></td><td>0.894881</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.36045</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td>Right</td><td>1.29873</td><td><b>1.29648</b></td><td>1.29873</td></tr>
    <tr><td>Avg.</td><td>1.32959</td><td><b>1.29824</b></td><td>1.29937</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0106</b></td><td>0.0729</td><td>0.1717</td></tr>
    <tr><td>Right</td><td><b>0.0071</b></td><td>0.0405</td><td>0.1089</td></tr>
    <tr><td>Avg.</td><td><b>0.00885</b></td><td>0.0567</td><td>0.1403</td></tr>
</table>
    

## Pose 6

**Description**: upper arms to the side and parallel to the ground; forearms and hands pointing up and
a bit to the back, forming a right angle with the upper arms. 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/5.jpg"></td>
    <td><img src="/images/poses/jacobian/5.jpg"></td>
    <td><img src="/images/poses/fabrik/5.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.815722</b></td><td>0.811068</td><td>0.803407</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>2.48564e-07</b></td><td>0.00285447</td><td>0.0102493</td></tr>
    <tr><td>Right</td><td><b>6.664e-08</b></td><td>0.00152383</td><td>0.00929935</td></tr>
    <tr><td>Avg.</td><td><b>1.57602e-07</b></td><td>0.00218915</td><td>0.00977434</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.68587e-07</b></td><td>0.0115463</td><td>0.0293615</td></tr>
    <tr><td>Right</td><td><b>8.42937e-08</b></td><td>0.0042278</td><td>0.0247809</td></tr>
    <tr><td>Avg.</td><td><b>1.26441e-07</b></td><td>0.00788705</td><td>0.0270712</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td><b>0.866235</b></td><td>0.863735</td><td>0.857599</td></tr>
    <tr><td>Right</td><td>0.903946</td><td><b>0.903946</b></td><td>0.89633</td></tr>
    <tr><td>Avg.</td><td><b>0.885091</b></td><td>0.883841</td><td>0.876965</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.35756</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td>Right</td><td>1.30404</td><td><b>1.29935</b></td><td>1.3</td></tr>
    <tr><td>Avg.</td><td>1.3308</td><td><b>1.29968</b></td><td>1.3</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0116</b></td><td>0.0762</td><td>0.2582</td></tr>
    <tr><td>Right</td><td><b>0.0073</b></td><td>0.0399</td><td>0.2182</td></tr>
    <tr><td>Avg.</td><td><b>0.00945</b></td><td>0.05805</td><td>0.2382</td></tr>
</table>
    

## Pose 7

**Description**: the standard T-pose; arms straight to the side and parallel to the ground; palms facing down; 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/6.jpg"></td>
    <td><img src="/images/poses/jacobian/6.jpg"></td>
    <td><img src="/images/poses/fabrik/6.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.76652</b></td><td>0.741975</td><td>0.757146</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>1.20137e-07</b></td><td>0.00130262</td><td>0.000142583</td></tr>
    <tr><td>Right</td><td><b>1.3411e-07</b></td><td>0.00122625</td><td>0.000850198</td></tr>
    <tr><td>Avg.</td><td><b>1.27124e-07</b></td><td>0.00126444</td><td>0.000496391</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.22878e-07</b></td><td>0.0271287</td><td>0.000146695</td></tr>
    <tr><td>Right</td><td><b>9.42432e-08</b></td><td>0.0257213</td><td>5.01819e-05</td></tr>
    <tr><td>Avg.</td><td><b>1.08561e-07</b></td><td>0.026425</td><td>9.84383e-05</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td><b>0.778936</b></td><td>0.778594</td><td>0.778861</td></tr>
    <tr><td>Right</td><td>0.840585</td><td><b>0.840684</b></td><td>0.840499</td></tr>
    <tr><td>Avg.</td><td><b>0.80976</b></td><td>0.809639</td><td>0.80968</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.28544</td><td><b>1.27395</b></td><td>1.28544</td></tr>
    <tr><td>Right</td><td>1.21354</td><td><b>1.19938</b></td><td>1.21354</td></tr>
    <tr><td>Avg.</td><td>1.24949</td><td><b>1.23666</b></td><td>1.24949</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0101</b></td><td>0.0772</td><td>0.131</td></tr>
    <tr><td>Right</td><td><b>0.0078</b></td><td>0.0415</td><td>0.1092</td></tr>
    <tr><td>Avg.</td><td><b>0.00895</b></td><td>0.05935</td><td>0.1201</td></tr>
</table>
    

## Pose 8

**Description**: the pose of someone holding an object up in front of oneself; arms slightly bent. 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/7.jpg"></td>
    <td><img src="/images/poses/jacobian/7.jpg"></td>
    <td><img src="/images/poses/fabrik/7.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td>0.832543</td><td><b>0.835825</b></td><td>0.826344</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>4.90155e-07</b></td><td>0.000802896</td><td>0.000711202</td></tr>
    <tr><td>Right</td><td><b>3.61641e-07</b></td><td>0.000190337</td><td>0.00036565</td></tr>
    <tr><td>Avg.</td><td><b>4.25898e-07</b></td><td>0.000496616</td><td>0.000538426</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.97686e-07</b></td><td>0.00488279</td><td>0.00367867</td></tr>
    <tr><td>Right</td><td><b>2.42573e-07</b></td><td>0.00428272</td><td>0.000152628</td></tr>
    <tr><td>Avg.</td><td><b>2.2013e-07</b></td><td>0.00458276</td><td>0.00191565</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>0.908585</td><td><b>0.92473</b></td><td>0.914281</td></tr>
    <tr><td>Right</td><td>0.877877</td><td><b>0.889876</b></td><td>0.877823</td></tr>
    <tr><td>Avg.</td><td>0.893231</td><td><b>0.907303</b></td><td>0.896052</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.31484</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td>Right</td><td><b>1.29357</b></td><td>1.29778</td><td>1.29357</td></tr>
    <tr><td>Avg.</td><td>1.3042</td><td>1.29889</td><td><b>1.29678</b></td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0114</b></td><td>0.0925</td><td>0.1269</td></tr>
    <tr><td>Right</td><td><b>0.0071</b></td><td>0.0406</td><td>0.1111</td></tr>
    <tr><td>Avg.</td><td><b>0.00925</b></td><td>0.06655</td><td>0.119</td></tr>
</table>
    

## Pose 9

**Description**: the pose of someone operating something on the table while standing; arms slightly bent. 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/8.jpg"></td>
    <td><img src="/images/poses/jacobian/8.jpg"></td>
    <td><img src="/images/poses/fabrik/8.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.798132</b></td><td>0.7741</td><td>0.793365</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>8.9407e-08</b></td><td>0.0105452</td><td>0.00186725</td></tr>
    <tr><td>Right</td><td><b>3.93755e-07</b></td><td>0.0108541</td><td>0.00193578</td></tr>
    <tr><td>Avg.</td><td><b>2.41581e-07</b></td><td>0.0106997</td><td>0.00190152</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.93141e-07</b></td><td>0.0505079</td><td>0.0328233</td></tr>
    <tr><td>Right</td><td><b>2.73143e-07</b></td><td>0.042835</td><td>0.0150312</td></tr>
    <tr><td>Avg.</td><td><b>2.33142e-07</b></td><td>0.0466714</td><td>0.0239273</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>0.866348</td><td>0.867067</td><td><b>0.873175</b></td></tr>
    <tr><td>Right</td><td>0.871757</td><td>0.873618</td><td><b>0.874999</b></td></tr>
    <tr><td>Avg.</td><td>0.869052</td><td>0.870343</td><td><b>0.874087</b></td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.24841</td><td><b>1.21924</b></td><td>1.2466</td></tr>
    <tr><td>Right</td><td>1.26812</td><td><b>1.24974</b></td><td>1.26837</td></tr>
    <tr><td>Avg.</td><td>1.25827</td><td><b>1.23449</b></td><td>1.25749</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0115</b></td><td>0.0762</td><td>0.2338</td></tr>
    <tr><td>Right</td><td><b>0.0068</b></td><td>0.0674</td><td>0.167</td></tr>
    <tr><td>Avg.</td><td><b>0.00915</b></td><td>0.0718</td><td>0.2004</td></tr>
</table>
    

## Pose 10

**Description**: the pose of someone sitting; elbows at the waist and pointing back; forearms pointing forward. 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/9.jpg"></td>
    <td><img src="/images/poses/jacobian/9.jpg"></td>
    <td><img src="/images/poses/fabrik/9.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.724998</b></td><td>0.724817</td><td>0.717264</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>2.78377e-07</b></td><td>0.00109942</td><td>0.000118717</td></tr>
    <tr><td>Right</td><td><b>3.1575e-07</b></td><td>0.000674893</td><td>0.000598625</td></tr>
    <tr><td>Avg.</td><td><b>2.97063e-07</b></td><td>0.000887157</td><td>0.000358671</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>2.73143e-07</b></td><td>0.0293805</td><td>0.0285485</td></tr>
    <tr><td>Right</td><td><b>2.68221e-07</b></td><td>0.0180183</td><td>0.0181389</td></tr>
    <tr><td>Avg.</td><td><b>2.70682e-07</b></td><td>0.0236994</td><td>0.0233437</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td><b>0.971101</b></td><td>0.929012</td><td>0.948063</td></tr>
    <tr><td>Right</td><td>1.02519</td><td><b>0.999521</b></td><td>1.01074</td></tr>
    <tr><td>Avg.</td><td><b>0.998148</b></td><td>0.964267</td><td>0.979401</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.4149</td><td><b>1.29572</b></td><td>1.3</td></tr>
    <tr><td>Right</td><td>1.36961</td><td><b>1.29979</b></td><td>1.3</td></tr>
    <tr><td>Avg.</td><td>1.39226</td><td><b>1.29776</b></td><td>1.3</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0134</b></td><td>0.0773</td><td>0.2265</td></tr>
    <tr><td>Right</td><td><b>0.0086</b></td><td>0.0658</td><td>0.1877</td></tr>
    <tr><td>Avg.</td><td><b>0.011</b></td><td>0.07155</td><td>0.2071</td></tr>
</table>
    

## Pose 11

**Description**: the pose of someone holding an object close in front of one's chest with two hands; arms acutely bend; 
upper arms parallel to the ground; 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/10.jpg"></td>
    <td><img src="/images/poses/jacobian/10.jpg"></td>
    <td><img src="/images/poses/fabrik/10.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td><b>0.800783</b></td><td>0.766429</td><td>0.779513</td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>5.37269e-07</b></td><td>0.0134984</td><td>0.000214801</td></tr>
    <tr><td>Right</td><td><b>4.09714e-07</b></td><td>0.0102553</td><td>0.000342506</td></tr>
    <tr><td>Avg.</td><td><b>4.73492e-07</b></td><td>0.0118768</td><td>0.000278653</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.89075e-07</b></td><td>0.0527762</td><td>0.0632329</td></tr>
    <tr><td>Right</td><td><b>1.19209e-07</b></td><td>0.0438051</td><td>0.04548</td></tr>
    <tr><td>Avg.</td><td><b>1.54142e-07</b></td><td>0.0482907</td><td>0.0543565</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>1.06414</td><td><b>0.954327</b></td><td>0.934574</td></tr>
    <tr><td>Right</td><td>1.07712</td><td><b>0.986143</b></td><td>0.974613</td></tr>
    <tr><td>Avg.</td><td>1.07063</td><td><b>0.970235</b></td><td>0.954594</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.55485</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td>Right</td><td>1.47476</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td>Avg.</td><td>1.51481</td><td>1.3</td><td><b>1.3</b></td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0113</b></td><td>0.0712</td><td>0.3102</td></tr>
    <tr><td>Right</td><td><b>0.0071</b></td><td>0.0367</td><td>0.2581</td></tr>
    <tr><td>Avg.</td><td><b>0.0092</b></td><td>0.05395</td><td>0.28415</td></tr>
</table>
    

## Pose 12

**Description**: the standard A-pose; arms straight and 45 degrees away from the body; palms facing inwards. 

### Images
<table>
<tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
<tr>
    <td><img src="/images/poses/onia/11.jpg"></td>
    <td><img src="/images/poses/jacobian/11.jpg"></td>
    <td><img src="/images/poses/fabrik/11.jpg"></td>
</tr>
</table>

### Metrics
    
<table>
    <tr><th colspan="2" rowspan="2">Metric</th><th colspan="3">Solvers</th></tr>
    <tr><th>ONIA (ours)</th><th>Jacobian</th><th>FABRIK</th></tr>
    <tr><td colspan="2">Overlay ratio</td><td>0.748028</td><td>0.772711</td><td><b>0.783473</b></td></tr>
    <tr><td rowspan="3">Wrist deviation (m)</td><td>Left</td><td><b>2.14908e-07</b></td><td>0.00293853</td><td>1.53082e-05</td></tr>
    <tr><td>Right</td><td><b>2.73143e-07</b></td><td>0.00190545</td><td>2.04843e-05</td></tr>
    <tr><td>Avg.</td><td><b>2.44025e-07</b></td><td>0.00242199</td><td>1.78963e-05</td></tr>
    <tr><td rowspan="3">Elbow deviation (m)</td><td>Left</td><td><b>1.51963e-07</b></td><td>0.030738</td><td>0.00133097</td></tr>
    <tr><td>Right</td><td><b>3.06834e-07</b></td><td>0.0240416</td><td>0.00322495</td></tr>
    <tr><td>Avg.</td><td><b>2.29398e-07</b></td><td>0.0273898</td><td>0.00227796</td></tr>
    <tr><td rowspan="3">Upper arm scaling</td><td>Left</td><td>0.769074</td><td><b>0.77749</b></td><td>0.769481</td></tr>
    <tr><td>Right</td><td>0.763186</td><td><b>0.768328</b></td><td>0.764131</td></tr>
    <tr><td>Avg.</td><td>0.76613</td><td><b>0.772909</b></td><td>0.766806</td></tr>
    <tr><td rowspan="3">Forearm scaling</td><td>Left</td><td>1.24287</td><td><b>1.23347</b></td><td>1.24287</td></tr>
    <tr><td>Right</td><td>1.21956</td><td><b>1.21535</b></td><td>1.21957</td></tr>
    <tr><td>Avg.</td><td>1.23122</td><td><b>1.22441</b></td><td>1.23122</td></tr>
    <tr><td rowspan="3">Computation time (s)</td><td>Left</td><td><b>0.0117</b></td><td>0.0737</td><td>0.1295</td></tr>
    <tr><td>Right</td><td><b>0.0074</b></td><td>0.0395</td><td>0.1127</td></tr>
    <tr><td>Avg.</td><td><b>0.00955</b></td><td>0.0566</td><td>0.1211</td></tr>
</table>
    