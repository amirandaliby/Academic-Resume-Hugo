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
  - title: Senior SW Infrastructure Architect | Network Infrastructures
    company: Nokia, IP Networks R&D
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
        * Network Infrastructures Regression ecosystem.
        * Autoregress: automate nightly regressions processing and execution (Bash and Python)
        * Build satellite topologies using SR7750 and IXR7250 routers to handle high-speed traffic exchange

  - title: Software Quality Assurance Engineer | SR Quality Assurance
    company: Nokia, IP Networks R&D
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
        
  - title: Tier II Network Engineer | Network Infrastructure Division
    company: Insurance Company of British Columbia (ICBC), Network and Data Center
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

  - title: Deep Packet Inspection (DPI) Analyst, SR Quality Assurance
    company: Nokia, IP Networks R&D
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
        
design:
  columns: '2'
---
