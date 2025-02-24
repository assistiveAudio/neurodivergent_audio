## Audio Comparison Table

Below is a comparison table with audio samples for different stimuli using four audio processing stages: **NN**, **DRC**, **GT** (Ground Truth), and **Mix**.  
Click the play button to listen to the corresponding audio files.


<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Audio Samples for Listening Test</title>
  <style>
    /* Style for the table */
    .audio-table {
      width: 100%;
      border-collapse: collapse; /* Merge table borders */
      margin: 0 auto;           /* Center the table horizontally */
    }
    /* Style for headers and cells */
    .audio-table th,
    .audio-table td {
      border: 1px solid #ccc;
      text-align: center;       /* Center text horizontally */
      vertical-align: middle;   /* Center text vertically */
      padding: 8px;             /* Space around text */
    }
    /* Style for the audio widget */
    .audio-table audio {
      width: 140px;  /* Adjust as needed */
      height: 30px;  /* Optional fixed height */
    }
  </style>
</head>
<body>

<table class="audio-table">
  <thead>
    <tr>
      <th>Trigger</th>
      <th>Non-Trigger</th>
      <th>NN</th>
      <th>DRC</th>
      <th>GT</th>
      <th>Mix</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>tap</td>
      <td>cricket</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_tap_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_tap_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_tap_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_tap_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>squeak</td>
      <td>waves</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_squeak_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_squeak_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_squeak_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_squeak_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>sniff</td>
      <td>camera noise</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_sniff_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_sniff_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_sniff_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_sniff_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>finger-snapping</td>
      <td>raining</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_finger-snapping_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_finger-snapping_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_finger-snapping_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_finger-snapping_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>slam</td>
      <td>river flowing</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_slam_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_slam_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_slam_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_slam_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>cutlery-silverware</td>
      <td>crows</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_cutlery,-silverware_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_cutlery,-silverware_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_cutlery,-silverware_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_cutlery,-silverware_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>chewing-mastication</td>
      <td>speech</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_chewing,-mastication_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_chewing,-mastication_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_chewing,-mastication_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_chewing,-mastication_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>breathing</td>
      <td>footsteps</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_breathing_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_breathing_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_breathing_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_breathing_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>alarm</td>
      <td>humming/singing</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_alarm_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_alarm_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_alarm_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_alarm_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

    <tr>
      <td>bark</td>
      <td>birds chirping</td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_bark_anc-nn.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_bark_anc-drc.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_bark_gt.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
      <td>
        <audio controls>
          <source src="{{ '/audio/SNR10_bark_mix.wav' | prepend: site.baseurl }}" type="audio/wav">
        </audio>
      </td>
    </tr>

  </tbody>
</table>

</body>
</html>



<!-- Analysis Section -->
<section id="analysis">
<div class="row">
<div class="col-lg-12">
<div class="text-center">
    <h2 class="section-heading">Analysis</h2>
</div>



<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My Figures</title>
  <style>
    .figure-row {
      display: flex;
      flex-direction: row;
      gap: 1rem;       /* space between columns */
      margin-bottom: 2rem;
    }
    .figure-col {
      flex: 1;         /* let each column expand to fill available space */
    }
    .iframe-container {
      border: 1px solid #ccc; 
      padding: 0.5rem;
    }
  </style>
</head>
<body>

  <!-- p3 in its own row -->
  <h3>Mean Triggerability across Trigger Labels</h3>
  <div class="iframe-container" style="margin-bottom: 2rem;">
    <iframe
      src="https://assistiveAudio.github.io/neurodivergent_audio/assets/p3"
      width="100%"
      height="500px"
      style="border: none;">
    </iframe>
  </div>

  <!-- p4 and p2 side by side -->
  <div class="figure-row">
    <div class="figure-col">
      <h3>Overall Mean Triggerability</h3>
      <div class="iframe-container">
        <iframe
          src="https://assistiveAudio.github.io/neurodivergent_audio/assets/p4"
          width="100%"
          height="500px"
          style="border: none;">
        </iframe>
      </div>
    </div>
    <div class="figure-col">
      <h3>Overall Mean Perceived Improvement</h3>
      <div class="iframe-container">
        <iframe
          src="https://assistiveAudio.github.io/neurodivergent_audio/assets/p2"
          width="100%"
          height="500px"
          style="border: none;">
        </iframe>
      </div>
    </div>
  </div>

  <!-- p1 in its own row -->
  <h3>Mean Perceived Improvement across Trigger Labels</h3>
  <div class="iframe-container">
    <iframe
      src="https://assistiveAudio.github.io/neurodivergent_audio/assets/p1"
      width="100%"
      height="400px"
      style="border: none;">
    </iframe>
  </div>

  <!-- Shared description for all four iframes -->
  <p style="margin-top: 1rem;">
    T-bars represent bootstrapped 95% confidence intervals. Stars indicate the 
    significance level of an algorithm having a higher perceived value than 
    the algorithm of comparison (<em>*p &lt; 0.05, **p &lt; 0.01, ***p &lt; 0.001</em>). 
    The color of the star indicates the algorithm of comparison. For the comparison, 
    a Friedman test was conducted, followed by a paired Wilcoxon Post-hoc test. 
    P-values were adjusted with Bonferroni.
  </p>

</body>
</html>







