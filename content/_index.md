---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        L2I Team
      image:
        filename: welcome.jpg
      text: |
        <br>
        Welcome to the L2I team webpage. 
        
        We are part of the <a href="http://golp.ist.utl.pt/">Group for Lasers and Plasmas</a>, <a href="http://ipfn.tecnico.ulisboa.pt/">IPFN</a>, <a href="http://tecnico.ulisboa.pt/">IST</a>.

        We develop and use state-of-the-art lasers and optical tools. Our research focuses on ultrafast science, nonlinear optics, and ultrashort laser technology, advancing fundamental understanding and cutting-edge applications.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '2'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: l2i-5.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
