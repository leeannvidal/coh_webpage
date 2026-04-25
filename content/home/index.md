---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
      title: Turn Hold Time Into Sales Opportunities
      text: Professional on-hold messages that keep callers engaged, reduce hang-ups, and promote your business while customers wait.
      primary_action:
        text: Get a Free Quote
        url: /contact-us
        icon: rocket-launch
      secondary_action:
        text: Hear Sample Messages
        url: /audio-showcase
    design:
        background:
            gradient:
                start: 'primary-500'
                end: 'primary-700'
                direction: 135
        spacing:
            padding: [0, 0, 0, 0]
            margin: [0, 0, 0, 0]
    #   # For full-screen, add `min-h-screen` below
    #   css_class: 'glassmorphism-dark glass-ring glass-shadow text-white'
    #   text_color: 'auto' # auto|light|dark
    #   overlay_opacity: 0.15 # 0.0-1.0 for contrast control
        
  - block: stats
    content:
      items:
        - statistic: "70%"
          description: |
            of callers placed on hold in silence hang up within 60 seconds
        - statistic: "30%"
          description: |
            of callers who hang up may never call back
        - statistic: "3x longer"
          description: |
            callers stay on hold when hearing useful information instead of silence
        - statistic: "93%"
          description: |
            of marketing budgets focus on making the phone ring—not what happens next
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Benefits of Professional On Hold Messages
      text: Turn every caller’s waiting time into a valuable marketing opportunity.
      items:
        - name: Reach a captive audience
          icon: users
          description: Speak directly to callers while they are already engaged and listening to your business.
        - name: Promote products and services
          icon: megaphone
          description: Highlight your latest services, key products, and important business updates while customers wait.
        - name: Reinforce marketing campaigns
          icon: speaker-wave
          description: Support your existing advertising by repeating key messages and strengthening brand recall.
        - name: Build brand awareness
          icon: building-office
          description: Keep your business memorable by consistently sharing your message with every caller.
        - name: Improve customer experience
          icon: face-smile
          description: Replace silence with helpful, professional messaging that improves the caller experience.
        - name: Reduce caller hang-ups
          icon: phone
          description: Keep callers on the line longer by providing useful information instead of silence or poor hold music.
        - name: Increase sales opportunities
          icon: chart-bar
          description: Turn every incoming call into a chance to upsell, cross-sell, and generate more revenue.
        - name: Promote offers and seasonal campaigns
          icon: gift
          description: Share limited-time promotions, seasonal offers, and important announcements instantly.
        - name: Strengthen your professional image
          icon: shield-check
          description: Create a polished first impression with professional voiceovers and high-quality messaging.
        - name: Turn hold time into valuable marketing time
          icon: clock
          description: Transform dead air into productive time that informs, reassures, and converts callers.
    design:
      columns: "3"
        #   background:
        #     color: "gray-50"
  - block: features
    id: services
    content:
      title: Services
    #   text: Turn every caller’s waiting time into a valuable marketing opportunity.
      items:
        - name: Professional Script Writing
          icon: check
        # - name: Professional Script Writing
        #   icon: check-circle
        - name: Voiceover Production
          icon: check-badge
        - name: Licensed Music
          icon: brands/leaflet
        - name: Custom On-Hold Messaging
          icon: brands/leaflet
        - name: Seasonal Updates
          icon: brands/leaflet
        - name: Multi-location Solutions
          icon: brands/leaflet
    design:
      columns: "2"
      background:
        color: "gray-50"

  - block: tech-stack
    id: skills
    content:
        title: "Services"
        categories:
            - name: Services
              items:
                - name: Professional Script Writing
                  icon: brands/leaflet
                - name: Voiceover Production
                  icon: brands/leaflet
                - name: Licensed Music
                  icon: brands/leaflet
                - name: Custom On-Hold Messaging
                  icon: brands/leaflet
                - name: Seasonal Updates
                  icon: brands/leaflet
                - name: Multi-location Solutions
                  icon: brands/leaflet
    design:
        style: list
        show_levels: false
#   - block: research-areas
#     content:
#         title: "Services"
#         items:
#             - name: "Professional Script Writing"
#               description: hello
#               emoji: ✅
#             #   topics:
#             #     - Genomics
#             #     - Proteomics
#             #     - Bioinformatics
#             #     - Systems Biology
#             - name: Voiceover Production
#               description: hello
#               icon: ✔️
#             - name: Licensed Music
#               description: hello
#             - name: Custom On-Hold Messaging
#               description: hello
#             - name: Seasonal Updates
#               description: hello
#             - name: Multi-location Solutions
#               description: hello
#               icon: "hero/book-open"
#     design:
#       layout: card      
  - block: cta-card
    content:
      title: Ready to Upgrade Your Caller Experience?
      text: Let’s create professional on-hold messaging that keeps callers engaged and helps your business stand out.
      button:
        text: Get Your Free Quote
        url: /contact-us
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---

<!-- #   - block: testimonials
#     content:
#       title: ""
#       text: ""
#       items:
#         - name: "Hugo Smith"
#           role: "Marketing Executive at X"
#           # Upload image to `assets/media/` and reference the filename here
#           image: "testimonial-1.jpg"
#           text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
#     design:
#       spacing:
#         # Reduce bottom spacing so the testimonial appears vertically centered between sections
#         padding: ["6rem", 0, 0, 0] -->

<!-- {{< card title="Fast" icon="bolt" subtitle="Built for speed" >}} -->
                <!-- {{< card title="Secure" icon="shield-check" subtitle="Security first" >}} -->

  - block: markdown
    content:
      title: "Services Markdown"
      subtitle: "More details below"
      text: |
          


                  <!-- {{< cards >}}
                {{< card url="../callout" title="Professional Script Writing" icon="check" >}}
                {{< card url="" title="Voiceover Production" icon="check-circle" >}}
                {{< card url="" title="Licensed Music" icon="check-badge" >}}
                {{< card url="" title="Custom On-Hold Messaging" icon="check-badge" >}}
                {{< card url="" title="Multi-location Solutions" icon="check-badge" >}}
            {{< /cards >}} -->
    design:
      columns: "1"
      background:
        color: "white"