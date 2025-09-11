+++
date = '2025-09-10T15:58:47-07:00'
draft = true
title = 'My First Post'
+++
## Test Header
This header is indeed test

## Welcome to My Hugo Site!

![Image description](images/my-image.png) <!-- replace with your image path -->

This is a sample text describing the content of the site.

### Audio Section

{{<audio src="media/audio/my-audio.wav" caption="your caption" >}}

<div class="audio-row">
  <audio controls>
    <source src="audio/my-audio.wav" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
  <audio controls>
    <source src="audio/my-audio.wav" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
  <audio controls>
    <source src="audio/my-audio.wav" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
</div>

<div class="audio-row">
  <audio controls>
    <source src="audio/my-audio.wav" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
  <audio controls>
    <source src="audio/my-audio.wav" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
  <audio controls>
    <source src="audio/my-audio.wav" type="audio/wav">
    Your browser does not support the audio element.
  </audio>
</div>

<style>
  .audio-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
  }
  audio {
    margin-right: 10px;
  }
</style>