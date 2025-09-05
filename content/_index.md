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
        url: uploads/Valerie_Li_CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: radiant-gradient.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    id: dissertation
    content:
      title: 'Dissertation and Book Project'
      subtitle: 'Speaking As One: The Logic of Collective Action Unity under Autocracy'
      text: |-
        
        ### **Speaking As One: The Logic of Collective Action Unity under Autocracy**
        
        Why do authoritarian states respond to civil resistance with low-level participation? I argue that the level of unity in contentious behaviors — the degree to which dissidents act in one and the same way — also matters. Even without large crowds, higher unity can threaten the state by disseminating a coherent political message, signaling protestors’ resolve, or revealing a shared societal grievance. My dissertation investigates what drives unified actions and how unity affects state response. Using text data on online public complaints in China, I show that action unity reduces the likelihood of state concessions for persistent single actors but increases it for group actors. A survey experiment in Thailand further reveals the conditions under which citizens join unified actions. My research advances the study of contentious politics by shifting focus from protest participation to the prevalence and impact of action unity in autocratic contexts. 

    design:
      columns: '1'
      css_class: 'text-wide'

#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2

#  - block: collection
#    id: papers
#    content:
#      title: Publication and Working Papers
#      text: ""
#      filters:
#        folders:
#          - publication
#        exclude_featured: false
#    design:
#      view: compact

  - block: markdown
    id: papers
    content:
      title: 'Publication and Working Papers'
      subtitle: ''
      text: |-
        
        **1. Thirst Traps and Quick Cuts: The Effects of TikTok 'Edits' on Evaluations of Politicians**, with Kevin Munger. Forthcoming at _Social Media + Society_. 

        **Abstract:** TikTok and the associated technologies for recording and editing short-form video constitute a large and growing portion of online communication. Previous modalities of social media, including static images and especially text, engendered significant attention to the facticity of the communication: was a statement true or false? Did an event actually take place? For a certain genre of stylized, highly edited short-form video, this is besides the point -- which is to produce a compelling video that portrays a prominent figure in a particular light. We conduct an experiment to evaluate whether "edits" of prominent politicians can change voter perceptions. We find that "thirst trap" edits cause an increase in perceptions of politician attractiveness, and that "badass" edits improve overall evaluations of Donald Trump (but not Joe Biden). Descriptively, we present a distribution of the evaluations of the attractiveness  of Trump, Biden, Bernie Sanders and Robert F. Kennedy Jr ("RFK"), demonstrating significant variation.  
        
        <br><br>

        **2. Learning Protest: How National Protest Contexts Influence Adolescents’ Views of Unconventional Political Participation**, with Lee Ann Banaszak and Shan-Jan Sarah Liu, Under Review at _Political Behavior_

        **Abstract:** Protest has become a normal form of political participation in many countries, although the degree to which protest is considered a legitimate form of civic engagement varies both across countries and across individuals within countries. This paper explores how national protest contexts influence adolescents’ protest propensity. Using cross-national surveys of 14-year-olds from 42 democracies, we show that adolescents are more willing to engage in lesser-known forms of peaceful protests than institutionalized, confrontational, or violent activities. Furthermore, using a quasi-experiment of a large protest of the G-20 meeting during the fielding of the 2009 survey in England, we demonstrate that a highly visible protest event can change adolescents’ propensity and attitude towards engaging in protest in the short run. This paper expands our knowledge of how national contexts affect adolescents’ different protest activities, raising implications for how democracies create environments that cultivate and improve civic engagement at a young age.  
        
        * Presented at 2023 Annual MPSA Conference, 2023

        <br><br>


        **3. Performing Loyalty: Does Adopting State Rhetoric Make Citizen’s Demands-making More Successful?”**, Under Review at _Comparative Political Studies_ 

        **Abstract:** Does performing loyalty to the state lead to better outcomes for citizens under authoritarian rule? Existing literature on civil resistance in authoritarian regimes implicitly assumes that when citizens adopt the language of the state in their claims-making, they increase their chances of success. However, using text data from China’s Mayor’s Mailbox—a digital petition platform through which citizens appeal to local leaders—I find adopting state rhetoric leads to worse outcomes. Further analysis reveals that this effect is conditional on the level of political threat. When demands are more threatening, state rhetoric becomes more effective. An online survey experiment in India supports the behavioral mechanisms uncovered in the observational data. These findings contribute to our understanding of everyday resistance under authoritarianism. Performing loyalty not only imposes costs but may also radicalize individuals following failed engagements with the state, thereby contributing to explaining autocratic instability and democratization.

        * Presented at 2024 Annual SPSA Conference, Conference-within-a-Conference:“The Politics of Authoritarian Regimes”

        <br><br>


        **4. Rethinking Collective Action: Cohesive Networks of Public Complaints in Authoritarian China**, Job Market Paper

        **Abstract:** What explains state repression of civil resistance with low-level participation? This paper argues that “cohesion” in contentious behaviors—agreement on demand goals
        or framing strategies—predicts state repression. Cohesive actions can emerge through collective efforts, imitation of others, or repeated behaviors by a single actor. Even without a large crowd, cohesive demands pose a threat to the state by disseminating a coherent political message about shared societal grievances. Using text data on online public complaints from China (N=135,147), I employ a text reuse detection method to identify cohesive networks of public complaints. Spatial analysis results demonstrate that engaging in cohesive actions reduces the likelihood of state concessions for a persistent single actor, but increases the likelihood of concession for group actors. This paper advances the study of contentious politics by moving beyond protest participation and revealing the prevalence and consequences of cohesive contentious behaviors in autocracies.

        * Scheduled to present at 2025 Annual APSA Conference and 2025 Fall Chinese Politics Research in Progress 


        <br><br>


        **5. Framing Conflict: Shifting Conflict Narratives during the Troubles in Northern Ireland**, with Cyanne E. Loyle
        
        **Abstract:** In times of war and peace, governments strategically use rhetoric to generate support for their policies and actions. Particularly in times of conflict, governments rally the troops and their country behind their war policies through the way they speak about and frame their actions. While scholars have long recognized the importance of rhetoric in politics, issue frames have been notoriously hard to measure. Recent methodological developments in natural language processing allow for new data to be brought to bear on the topic of how issues are framed. Furthermore, these innovations allow for new theoretical advances in how and why frame shifts occur. Using these techniques, we examine the concept of dynamic issue framing in the case of the thirty-year civil war in Northern Ireland. We identify the dominant conflict frames propagated by the British government and study the conditions under which these frames shift overtime. How governments talk about a conflict matters for its policies as well as public support for its actions. Through understanding how the British government framed its engagement in Northern Ireland we can learn more about the politics of issue framing in democracies at war and beyond.

        * Presented at Online Peace Science Colloquium, 2023
        * Presented at Junior Scholars in Quantitative Conflict, 2024


        <br><br>


        **6. Drivers of Connective Actions: Evidence from Two Survey Experiments"**, Works in Progress
        
        
        **7. State Repression and the Law: Domestic Lawfare, Autocratic Legalism, and the Future of the Judiciary"**, with Cyanne E. Loyle, Cecilia Cavero Sánchez and Lesley Zhang
        
    design:
      columns: '1'
      css_class: 'text-wide'
  
  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      subtitle: ''
      text: |-
        
        **Teaching Assistant:** PLSC 498 Text-As-Data, Fall 2022

        **Graduate Advisor:** Political Science Horizons at Penn State, Fall 2022

        * Undergraduate mentorship program for career success in Political Science 

        **Guest Lecture:** GLIS 102 Global Pathways, Spring 2025
        *  "Human Rights and Regime Type"

        **Workshop Instructor:** Open Scholarship Bootcamp, Summer 2025
        *  "LLMs with Jupyter Notebooks", '[workshop materials](/uploads/LLM tutorial for 2025 Open Scholarship Bootcamp.ipynb)'

    design:
      columns: '1'
      css_class: 'text-wide'

#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1

#- block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#       tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
      # Choose a layout view
#      view: date-title-summary
      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
---
