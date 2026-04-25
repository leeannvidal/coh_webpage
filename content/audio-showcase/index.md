---
title: "Audio Showcase"
type: landing
sections:
  - block: features
    id: audio-categories # Assign an ID for internal linking
    content:
      title: "Explore Our Audio Collection"
      text: "Listen to a variety of audio samples across different categories."
      items:
        - name: "Music"
          icon: "music" # Using a generic music icon, you can explore other options if available
          description: "Dive into instrumental tracks, classical pieces, and modern compositions."
          url: "/audio-showcase/music/" # Link to a sub-page for music
        - name: "Voice"
          icon: "microphone" # Using a generic microphone icon
          description: "Discover a range of voice talent for narrations, promos, and more."
          url: "/audio-showcase/voice/" # Link to a sub-page for voice
        - name: "Messages"
          icon: "volume-up" # Using a generic volume icon
          description: "Pre-recorded messages for on-hold, public address, and radio."
          url: "/audio-showcase/messages/" # Link to a sub-page for messages
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper on LLMs
          icon: academicons/arxiv
          url: https://arxiv.org/abs/2304.01852
        - text: Watch my new YouTube video to achieve 20x productivity
          icon: brands/youtube
          url: https://youtube.com
        - text: Connect with me on LinkedIn
          icon: brands/linkedin
          url: https://linkedin.com
---

## Music Samples

### Classical
{{< audio src="audio/music/classical/sample.mp3" >}}

### Light Jazz
{{< audio src="audio/music/lightjazz/sample2.mp3" >}}

## Voice Samples

### Aurora
{{< audio src="audio/voice/Aurora.mp3" >}}

### Debbie
{{< audio src="audio/voice/Debbie.mp3" >}}