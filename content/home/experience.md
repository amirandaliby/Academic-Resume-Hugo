---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Recent Work Experience
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
  - title: Software Quality Assurance Engineer, Infrastructures
    company: Nokia Canada, IP Networks R&D
    company_url: ''
    location: 'Ottawa, ON'
    date_start: '2023-01-01'
    date_end: ''
    description: |2-
        Responsibilities:
        * End-to-end feature testing on 7705 SAR product family
        * Test development & automation in TCL, Bash, Python, and Perl
        * Containerization, CI/CD, config management systems (Puppet, Ansible)
        * System administration: Linux RPM & DEB

        Projects:
        * Autoregress: automate nightly regressions processing and execution (Bash and Python)
        * Build satellite topologies using SR7750 and IXR7250 routers to handle high-speed traffic exchange

  - title: Software Quality Assurance Engineer, Deep Packet Inspection (DPI)
    company: Nokia Canada, IP Networks R&D
    company_url: ''
    location: 'Ottawa, ON'
    date_start: '2018-05-01'
    date_end: '2022-12-31'
    description: |2-
        Responsibilities:
        * Software QA and traffic detection on 7x50 service routers
        * Test development  & automation: TCL/Bash/Python scripting
        * Containerization: Docker, Swarm, K8
        * Lab maintenance & System administration: Linux RPM & DEB, Windows, and macOS
        * Elasticsearch administration
        * Co-op training and supervision

        Projects:
        * Automation of DNS over HTTPS (DoH) and DNS over TLS (DoT) server check and traffic generation on mobile and web (Appium and Selenium)
        * Automation of Mobile and web traffic generation and analysis with Appium and Selenium using docker written in Bash, Python (BDD method) and Perl
        * Build Elasticsearch with Beats data shippers: Filebeat and Metricbeat to handle Cflowd records over Logstash
        * Deliver full ELK stack setup over docker for traffic logging 
        * TCL test development for encrypted SNI in QUIC and TLS1.3
        * Shared Network Storage (NAS) setup
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

  # - title:  Network Engineer 
  #   company: Mobile Communication Company of Iran (MCI), Radio Access Network
  #   company_url: ''
  #   location: 'Tehran, Iran'
  #   date_start: '2013-12-01'
  #   date_end: '2015-08-30'
  #   description: |2-
  #       Responsibilities:
  #       * Top-level monitoring and troubleshooting of Radio Network Controllers (RNCs) for over 300 stations, serving over 25000 NodeB cells and 65 million subscribers
  #       * Operation and maintenance, data configuration, and troubleshooting of WCDMA and LTE RAN equipment (Huawei and Ericsson equipment)
  #       * OptiX NG SDH equipment commissioning and maintenance (Huawei equipment)

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
