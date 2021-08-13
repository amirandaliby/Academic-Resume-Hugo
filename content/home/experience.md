---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Work Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Quality Assurance Engineer
    company: Nokia Canada, IP Networks R&D
    company_url: ''
    location: 'Ottawa, ON'
    date_start: '2018-05-01'
    date_end: ''
    description: |2-
        Responsibilities:
        * AnalysingSoftware QA and traffic detection on 7x50 service routers
        * Test development  & automation: TCL/Bash/Python scripting
        * DevOps: containerization, CI/CD, task automations 
        * Lab maintenance & System administration: Linux RPM & DEB
        * Elasticsearch administration
        * Co-op training and supervision

        Projects:
        * Mobile and web Task automation CI/CD with Ansible, Appium, Selenium using docker and orchestrated by Jenkins
        * Deliver full ELK stack setup over docker for traffic logging 
        * TCL test development for encrypted SNI in QUIC and TLS1.3
        * Shared Network Storage (NAS)
        * Countless number of HW, system and VM setups for testing
        
  - title: Tier II Network Engineer, Co-op
    company: Insurance Company of BC (ICBC), Network and Data Center
    company_url: ''
    location: 'Vancouver, BC'
    date_start: '2018-01-01'
    date_end: '2018-04-30'
    description: |2-
        Responsibilities:
        * L2/L3 devices installment, configuration, and troubleshooting (Cisco routers and switches)

        Projects:
        * WLAN redesign using Ekahau ESS, ESS spectrum analyzer
        * Cisco configuration automation using Ansible

  - title: Deep Packet Inspection (DPI) Analyst, Co-op
    company: Nokia Canada, IP Networks R&D
    company_url: ''
    location: 'Ottawa, ON'
    date_start: '2017-09-01'
    date_end: '2018-12-30'
    description: |2-
        Responsibilities:
        * L3/L4 traffic inspection to check traffic detection functionality on the 7x50 service routers platform
        * Quality assurance of signatures for applications and protocols  

        Projects:
        * Socket programming on Python
        * Setup test environments, including simulators, virtual machines, hardware, and workstations

  - title:  Co-Founder and Managing Director 
    company: RTP-Owj Co.
    company_url: ''
    location: 'Tehran, Iran'
    date_start: '2013-12-01'
    date_end: '2015-08-30'
    description: |2-
        Projects:
        * eTourism platform for Iran Cultural Heritage Handicrafts and Tourism Organization (ICHTO) and Iran Post

  - title:  Network Engineer 
    company: Mobile Communication Company of Iran (MCI), Radio Access Network
    company_url: ''
    location: 'Tehran, Iran'
    date_start: '2013-12-01'
    date_end: '2015-08-30'
    description: |2-
        Responsibilities:
        * Top-level monitoring and troubleshooting of Radio Network Controllers (RNCs) for over 300 stations, serving over 25000 NodeB cells and 65 million subscribers
        * Operation and maintenance, data configuration, and troubleshooting of WCDMA and LTE RAN equipment (Huawei and Ericsson equipment)
        * OptiX NG SDH equipment commissioning and maintenance (Huawei equipment)

  - title:  Techinical Manager 
    company: Telka Mobin Sanat Co.
    company_url: ''
    location: 'Tehran, Iran'
    date_start: '2013-03-01'
    date_end: '2015-11-30'
    description: |2-
        Projects:
        * Transmission Installment (TI), node upgrade, and radio drive test & optimization in several provinces of Iran
        
design:
  columns: '2'
---