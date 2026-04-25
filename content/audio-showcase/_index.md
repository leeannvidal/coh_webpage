---
title: "Audio Showcase"
type: landing

sections:
  # - block: features
  #   id: audio-categories # Assign an ID for internal linking
  #   content:
  #     title: Explore Our Audio Collection"
  #     text: "Listen to a variety of audio samples across different categories."
  #     items:
  #       - name: "Music"
  #         icon: musical-note
  #         description: "Dive into instrumental tracks, classical pieces, and modern compositions."
  #         url: "/audio-showcase/music/" # Link to a sub-page for music
  #       - name: "Voice"
  #         icon: "microphone" # Using a generic microphone icon
  #         description: "Discover a range of voice talent for narrations, promos, and more."
  #         url: "/audio-showcase/voice/" # Link to a sub-page for voice
  #       - name: "Messages"
  #         icon: speaker-wave
  #         description: "Pre-recorded messages for on-hold, public address, and radio."
  #         url: "/audio-showcase/messages/" # Link to a sub-page for messages
  - block: faq
    content:
      title: Explore Our Audio Collection
      subtitle: Listen to a variety of audio samples across different categories.
      text: Can't find what you're looking for? [Contact us](/contact)
      items:
        - question: Music
          answer: |
            Dive into instrumental tracks, classical pieces, and modern compositions.
            {{< button url="/audio-showcase/music/" style="outline" rounded="full" icon="musical-note" icon_position="right" >}}Music{{< /button >}}
        
        - question: Voice
          answer: |
            Discover a range of voice talent for narrations, promos, and more.
            {{< button url="/audio-showcase/voice/" style="outline" rounded="full" icon="microphone" icon_position="right" >}}Voice{{< /button >}}
        
        - question: Messages
          answer: |
            Pre-recorded messages for on-hold, public address, and radio.
            {{< button url="/audio-showcase/messages/" style="outline" rounded="full" icon="speaker-wave" icon_position="right" >}}Messages{{< /button >}}
    design:
      spacing:
        padding: ["6rem", "0", "6rem", "0"]

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

  # - block: cta-button-list
  #   content:
  #     # Need a custom icon?
  #     # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
  #     buttons:
  #       - text: Music
  #         icon: musical-note
  #         url: " "
  #       - text: Voice
  #         icon: microphone
  #         url: https://youtube.com
  #       - text: Messages
  #         icon: speaker-wave
  #         url: https://linkedin.com

    - block: logos
    content:
      title: Explore Our Audio Collection
      subtitle: Listen to a variety of audio samples across different categories.
      text:
      logos:
        - name: Music
          image: coffee.jpg
          url: /audio-showcase/music/
          description: Dive into instrumental tracks, classical pieces, and modern compositions.
        - name: Voice
          image: coffee.jpg
          url: /audio-showcase/voice/
          description: Discover a range of voice talent for narrations, promos, and more.
        - name: Messages
          image: coffee.jpg
          url: /audio-showcase/messages
          description: Pre-recorded messages for on-hold, public address, and radio.
    design:
      display_mode: marquee
      # css_class: "bg-gray-50 dark:bg-gray-900"