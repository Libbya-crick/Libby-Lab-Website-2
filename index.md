---
dark: true
---

<div style="background-image: url('images/Libby_Avian_image.png'); background-size: cover; background-position: center; min-height: 50vh; padding: 20px;">
  <div style="max-width: 1200px; margin: 0 auto; background-color: rgba(13, 17, 23, 0.9); padding: 40px; border-radius: 10px;">
    <h1 style="font-size: 2rem;"><span style="color: var(--tirtiary)">Connecting molecular to morphogenic</span></h1>

    The Libby Lab is interested in understanding how tissues are generated from limited starting populations of stem cells. This process is remarkable as it involves the coordination of individual cellular units that need to interpret a complex environment, specify end fate, and physically move into place. Further, this must occur in a coordinated manner with neighbouring cells to build functional tissues. To break down the complex process of tissue generation into key components, we think about the following questions:

    **1) What collective cell behaviours inform morphogenesis and tissue building?**

    **2) How do populations of stem cells interpret complex environments?** 

    **3) What cell intrinsic mechanisms buffer stem cell specification against changing environments?**
  </div>
</div>

<div style="background-color: var(--background); padding: 20px;">
  <div style="max-width: 1200px; margin: 0 auto; padding: 40px;">
    {% include section.html %}

    {% capture text %}

    To begin to answer these questions, we use the developing spinal cord as a model examine how cell fate decisions and tissue scale morphogenesis interact, forming feedback loops to connect population level behaviours to individual cell internal and external environments.

    {%
      include button.html
      link="research"
      text="Want to know more? See our research"
      icon="fa-solid fa-arrow-right"
      flip=true
      style="bare"
    %}

    {% endcapture %}

    {%
      include feature.html
      image="images/background.jpg"
      link="research"
      title="<span style='color: var(--secondary)'>Our Research</span>"
      text=text
      style = "bare"
    %}

    {% capture text %}

    Lab opening in January 2026! We are actively recruiting scientists at all levels passionate about embryonic development, tissue engineering, and epigenetic regulation of fate.

    {%
      include button.html
      link="team"
      text="Meet our team"
      icon="fa-solid fa-arrow-right"
      flip=true
      style="bare"
    %}

    {% endcapture %}

    {%
      include feature.html
      image="images/libby-lab-eggs.png"
      link="team"
      title="<span style='color: var(--secondary)'>Our Team</span>"
      flip=true
      style = "bare"
      text=text
    %}

    {% capture text %}

    Explore our published research and scientific contributions in developmental biology, stem cell research, and tissue engineering.

    {%
      include button.html
      link="papers"
      text="View our publications"
      icon="fa-solid fa-arrow-right"
      flip=true
      style="bare"
    %}

    {% endcapture %}

    {%
      include feature.html
      image="images/Screen-website-paper.png"
      link="papers"
      title="<span style='color: var(--secondary)'>Our Papers</span>"
      text=text
      style = "bare"
    %}
  </div>
</div>
