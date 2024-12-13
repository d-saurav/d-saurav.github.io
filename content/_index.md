---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Research Overview'
      subtitle: ''
      text: |-
        My research journey has been a mosaic of interconnected explorations, each phase building on the other, revealing the fascinating tapestry of mechanics and materials. It began with the tremors of the earth and has evolved into designing materials that shape the future of engineering.

        ### **Listening to the Earth: Ground Motion and Seismic Dynamics**  
        It started with a simple yet profound question: How can we better understand the forces that shake our world? My early work focused on the dynamics of ground motion, where I dived into seismic data, unraveling patterns hidden within the chaos of earthquakes. Using tools like MATLAB and datasets from the PEER database, I calculated response spectra, peak ground accelerations, and Fourier spectra, turning raw data into meaningful insights. These studies were not just about numbers; they were about safeguarding lives, creating structures that could withstand nature’s fury, and finding harmony within disorder.

        ### **Mechanical Systems: Precision in Motion**
        As my curiosity grew, I looked upward—toward engineered systems where precision and control reign supreme. I explored the dynamics of time-periodic stiffness in a single-degree-of-freedom system, designing experiments that brought theory to life. With pendulums crafted to perfection and motors synchronized to the microsecond, I delved into the subtle dance between motion and mechanics. Techniques like Laser Doppler Vibrometry and Digital Image Correlation became my tools, helping me track the oscillations of these systems with pinpoint accuracy. Each experiment felt like tuning a symphony, seeking the perfect resonance in a sea of possibilities.

        ### **Metamaterials: The Art of Shaping Waves**
        This fascination with dynamics and control naturally led me to metamaterials—engineered marvels that manipulate waves in ways once thought impossible. Here, the challenge was to create materials that defied conventional boundaries. By designing topological metamaterials, I entered a realm where structure dictates function, where geometry holds the key to phenomena like wave propagation and energy localization. It was in this phase that I began exploring the concept of inverse design, using physics and computation not only to understand but to create.

        ### **The Inverse Design of Heterogeneous Materials: Complexity Meets Creativity**
        Today, my journey has brought me to the cutting edge of material science: the inverse design of heterogeneous materials. Working with Prof. Akshay Joshi at IISc, I am leveraging data-driven techniques to uncover the hidden potential of materials with spatially varying properties. By clustering material behaviors, calculating deformation gradients, and harnessing computational frameworks, I aim to craft materials that respond to the most demanding applications. This phase feels like a culmination of everything before it—a blending of the precision from mechanical systems, the innovation from metamaterials, and the complexity from seismic dynamics.

        ### **A Vision of Interconnected Ideas**
        As I reflect on this journey, I see a story of connections—how the tremors of the earth inspired a fascination with motion, how motion led to the discovery of materials that defy convention, and how all of it converged into designing the impossible. My research is not just about solving problems; it’s about weaving together threads of curiosity and innovation to create something meaningful, something lasting.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
