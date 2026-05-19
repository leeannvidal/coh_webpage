---
title: 'Services'
date: 2026-04-25
type: landing

sections:
  - block: page-header
    content:
      title: "Our Services"
      # title: "Coding Corner: <br>Tools & Resources"
      subtitle: 
    design:
      background:
        color: var(--color-primary-900)
        # color: '#0A57B7'
        text_color: '#F2F2F2'
      spacing:
        padding: ["1rem", "0", "1rem", "0"]
#   - block: hero
#     content:
#       title: Professional Audio Messaging Services
#       text: From on-hold messages to auto-attendant greetings, IVR recordings, radio commercials, and in-store announcements, we help your business sound professional at every customer touchpoint.
#       primary_action:
#         text: "Request a Quote"
#         url: 'mailto:lorib@communicationsonhold.com?subject=Request a Quote – Website Enquiry'
#         icon: rocket-launch
  - block: features
    id: services-2
    content:
        # title: 
        # title: Our Services
        text: Professional voice, music, and messaging solutions designed to improve customer experience, promote your business, and strengthen your brand.
        items:
        - name: On-Hold Messages
          icon: phone
          description: Custom on-hold messaging that keeps callers engaged, promotes your products and services, and helps reduce hang-ups.
        - name: Auto-Attendant Greetings & IVR
          icon: queue-list
          description: Clear, professional recordings for day greetings, after-hours messages, menus, call routing, and voicemail systems.
        - name: Radio Commercials
          icon: radio
          description: Professionally written and produced radio ads with quality voiceovers, music, and production to help your message stand out.
        - name: Overhead Store Announcements
          icon: speaker-wave
          description: In-store announcements that promote offers, highlight products, and influence customers while they are already in your business.
        - name: Call Caddy
          icon: megaphone
          description: Help every call sound professional, even when your team is busy, with recorded messages and call support options.
        - name: Custom Voice Production
          icon: microphone
          description: Professional voice recordings for phone systems, websites, presentations, training materials, and business announcements.
    design:
        columns: "3"
        spacing:
          padding: ["0", 0, "0", "0"]
  # - block: cta-image-paragraph
  #   content:
  #     items:
  #       # - title:
  #       - title: How It Works
  #         # text: Getting professional audio for your business is simple
  #         feature_icon: ""
  #         # feature_icon: bolt
  #         features:
  #           "**1. We Learn About Your Business -**
  #           We listen to your goals, services, promotions, and brand style so your message feels tailored to your company. <br><br>
  #           **2. We Write Your Script -**
  #           Our copywriters create clear, engaging messages designed to inform callers and promote your business. <br><br>
  #           **3. You Choose Voice & Music -** 
  #           Select the voice talent and music style that best matches your company image. <br><br>
  #           **4. We Produce the Audio -**
  #           Your final recording is professionally produced, mixed, and mastered for clear, high-quality playback. <br><br>
  #           **5. We Help You Get Set Up -**
  #           Once approved, your finished audio is prepared for your phone system or chosen platform."
  #         image: images/coh_services.png
  #   design:
  #     spacing:
  #       padding: ["0", "0", "0", "0"]
  - block: steps
    content:
      title: How It Works
      items:
        - title: We Learn About Your Business
          text: We listen to your goals, services, promotions, and brand style so your message feels tailored to your company.
          # icon: rectangular-stack
        - title: We Write Your Script
          text: Our copywriters create clear, engaging messages designed to inform callers and promote your business.
          # icon: rectangular-stack
        - title: You Choose Voice & Music
          text: Select the voice talent and music style that best matches your company image.
          cta: 
            text: Browse samples here
            url: ../audio-showcase/
          # icon: rectangular-stack
        - title: We Produce the Audio
          text: Your final recording is professionally produced, mixed, and mastered for clear, high-quality playback.
          # icon: rectangular-stack
        - title: We Help You Get Set Up
          text: Once approved, your finished audio is prepared for your phone system or chosen platform.
          # icon: rectangular-stack
    design:
      # layout: horizontal
      marker_style: icon
      connector: dashed
      spacing:
        padding: ["0", "0", "0", "0"]
  - block: contact-cta-card
    content:
        title: Ready to Improve How Your Business Sounds?
        text: Whether you need on-hold messages, IVR greetings, radio ads, or in-store announcements, we can help you create professional audio that makes the right impression.
        button:
            text: Request a Quote
            url: 'mailto:lorib@communicationsonhold.com?subject=Request a Quote – Website Enquiry'
            # url: /contact
    design:
      spacing:
        padding: ["0", ".5rem", "0", ".5rem"]
        # padding: ["0", 0, "0", "0"]
      card:
        css_class: 'glassmorphism-primary glass-ring glass-shadow text-white'
        text_color: 'light' # auto|light|dark
        text_align: center
        text_width: max-w-5xl
        overlay_opacity: 0.15 # 0.0-1.0 for contrast control
---
