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
      title: 'Book Project'
      subtitle: 'Contentious Unity: Networks of Public Grievances in China'
      text: |-
        While the repression literature focuses on the threat of coordinated actions against the state, this book project establishes an alternative pathway that explains repression despite low-level participation. It captures the unity of dissident actions where groups act together in similar ways. Ideas become more threatening to the state when they are seen as coordinated, thus identifying a latent grievance. Therefore, I argue that the state is more likely to repress when contentious actions are unified even given low levels of participation or coordination. Furthermore, I argue that aggrieved citizens participate in contentions actions despite the risk of repression, especially when demanding private goods, when the leadership shows tactical competence, and when participants share common demographic attributes. 
        
        
        I test my theory using administrative data from China’s petitioning platform, the Mayor’s Mailbox. The Mayor’s Mailbox is a public forum that allows citizens to register grievances against local government. This data source allows me to identify collective action potential in an authoritarian regime with historically little space for public dissent. Using a novel text reuse detection algorithm, the S-W algorithm, I measure and validate whether two individually submitted petitions contain a high degree of textual alignment and, thus, are suspects of group actions. These dyadic relationships thus form networks of public grievances in China. Empirical chapters of my dissertation find that approximately 13% of all petitions submitted to the Mayor’s Mailbox have at least one connection to another petition. Furthermore, spatial analysis shows local governments tend to make concessions to unified petitions submitted by a group but punish repetitive petitions submitted by an individual. Lastly, survey experiments conducted in Thailand and India also show support for my arguments. 

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
        
        **1. Thirst Traps and Quick Cuts: The Effects of TikTok 'Edits' on Evaluations of Politicians**, with Kevin Munger. Accepted and Forthcoming at _Social Media + Society_. 

        **Abstract:** TikTok and the associated technologies for recording and editing short-form video constitute a large and growing portion of online communication. Previous modalities of social media, including static images and especially text, engendered significant attention to the facticity of the communication: was a statement true or false? Did an event actually take place? For a certain genre of stylized, highly edited short-form video, this is besides the point -- which is to produce a compelling video that portrays a prominent figure in a particular light. We conduct an experiment to evaluate whether "edits" of prominent politicians can change voter perceptions. We find that "thirst trap" edits cause an increase in perceptions of politician attractiveness, and that "badass" edits improve overall evaluations of Donald Trump (but not Joe Biden). Descriptively, we present a distribution of the evaluations of the attractiveness  of Trump, Biden, Bernie Sanders and Robert F. Kennedy Jr ("RFK"), demonstrating significant variation.  
        
        
        **2. Performing Loyalty: Does Adopting State Rhetoric Make Citizen’s Demands-making More Successful?”** 

        **Abstract:** Does performing loyalty to the state lead to better outcomes for citizens under authoritarian rule? Existing literature on civil resistance in authoritarian regimes implicitly assumes that when citizens adopt the language of the state in their claims-making, they increase their chances of success. However, using text data from China’s Mayor’s Mailbox—a digital petition platform through which citizens appeal to local leaders—I find adopting state rhetoric leads to worse outcomes. Further analysis reveals that this effect is conditional on the level of political threat. When demands are more threatening, state rhetoric becomes more effective. An online survey experiment in India supports the behavioral mechanisms uncovered in the observational data. These findings contribute to our understanding of everyday resistance under authoritarianism. Performing loyalty not only imposes costs but may also radicalize individuals following failed engagements with the state, thereby contributing to explaining autocratic instability and democratization.


        **3. Learning Protest: How National Protest Contexts Influence Adolescents’ Views of Unconventional Political Participation**, with Lee Ann Banaszak, Shan-Jan Sarah Liu, and Burcin Tamer, Under Review at the _American Journal of Political Science_

        **Abstract:** Protest has become a normal form of political participation in many countries, although the degree to which protest is considered a legitimate form of civic engagement varies both across countries and across individuals within countries. This paper explores how national protest contexts influence adolescents’ protest propensity. Using cross-national surveys of 14-year-olds from 42 democracies, we show that adolescents are more willing to engage in lesser-known forms of peaceful protests than institutionalized, confrontational, or violent activities. Furthermore, using a quasi-experiment of a large protest of the G-20 meeting during the fielding of the 2009 survey in England, we demonstrate that a highly visible protest event can change adolescents’ propensity and attitude towards engaging in protest in the short run. This paper expands our knowledge of how national contexts affect adolescents’ different protest activities, raising implications for how democracies create environments that cultivate and improve civic engagement at a young age.  
        
        
        **4. Framing Conflict: Shifting Conflict Narratives during the Troubles in Northern Ireland**, with Cyanne E. Loyle
        
        **Abstract:** In times of war and peace, governments strategically use rhetoric to generate support for their policies and actions. Particularly in times of conflict, governments rally the troops and their country behind their war policies through the way they speak about and frame their actions. While scholars have long recognized the importance of rhetoric in politics, issue frames have been notoriously hard to measure. Recent methodological developments in natural language processing allow for new data to be brought to bear on the topic of how issues are framed. Furthermore, these innovations allow for new theoretical advances in how and why frame shifts occur. Using these techniques, we examine the concept of dynamic issue framing in the case of the thirty-year civil war in Northern Ireland. We identify the dominant conflict frames propagated by the British government and study the conditions under which these frames shift overtime. How governments talk about a conflict matters for its policies as well as public support for its actions. Through understanding how the British government framed its engagement in Northern Ireland we can learn more about the politics of issue framing in democracies at war and beyond.
        
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


        **Guest Lecture:** GLIS 102 Global Pathways, Spring 2025


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
