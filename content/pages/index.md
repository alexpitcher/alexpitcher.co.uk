---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: ALEX pitcher portfolio
    subtitle: Welcome to my portfolio
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: Skills
    subtitle: ''
    text: "### Networking & IT Infrastructure\n\n•\tExperience with modern Cisco equipment, Cisco IOS, OSPFv2, router and switch configuration\n\n•\tExperience with modern HPE networking equipment, Aruba Gateways, AOS-S, AOS-CX and Comware based switches, ArubaOS 8 & 10 Access Points, routing protocols, and modern cloud-based network configuration\n\n•\tPractical lab skills including Linux, firewall configurations, Windows directories/domains, certificate authorities, and remote VDI\n\n•\tExpertise in cutting-edge network technologies (WiFi 7, Private 5G, SD-WAN)\n\n•\tProficiency in cloud networking: deploying and managing solutions on Oracle Cloud, Google Cloud, and AWS\n\n•\tSystem administration: deploying, configuring, and maintaining enterprise server and infrastructure equipment\n\n•\tExperience in network auditing, upgrading IT systems, and network automation using tools such as Ansible and Terraform\n\n### Programming & Automation\n\n•\tStrong Python background (from early education to university), with secure coding practices and automation projects (e.g., smart home systems)\n\n•\tFamiliarity with C and C++\n\n•\tApplication of programming skills to network automation and infrastructure deployment\n\n### Communication & Project Management\n\n•\tClient interaction and project scoping to design and deliver tailored network solutions\n\n•\tExperience in managing projects from initial design through post-implementation reviews\n\n•\tInvolvement in sales efforts and client-facing demonstrations, including working with channel organisations\n\n### Practical & Technical Abilities\n\n•\tHands-on skills demonstrated through personal projects (e.g., designing, fabricating, and painting wooden planters; exterior painting projects)\n\n•\tTechnical theatre experience: lighting design, sound operations, and technical management for productions and freelance work\n\n### Language Skills\n\n•\tProficiency in French (studied since a young age and practiced in real-world settings)\n"
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
  - type: TextSection
    colors: colors-c
    variant: variant-a
    title: Education
    subtitle: ''
    text: "### GCSE GRADES:\n\n10 GCSEs, including Maths and English at Grade 7\n\n### A LEVEL GRADES:\n\nOCR Computer Science: A\n\nOCR Mathematics: C\n\nAQA French: D\n\n### Education\n\n#### 2022 – Present\n\nDe Montfort University – Computer Networks and Security (BSc)\n\n•\tPursued a BSc in Computer Networks and Security blending networks, security, and programming\n\n•\tCompleted specialised Cisco-aligned networking modules covering various Cisco certifications\n\n•\tGained practical experience through state-of-the-art labs designed in collaboration with Cisco\n\n•\tEnhanced skills in secure coding, network development, and cyber security through lectures, seminars, and lab work\n\n•\tPrepared for diverse roles in the field of computer networks and security\n\n#### 2011 – 2022\n\nKing Henry VIII School\nYEAR 4 – YEAR 11\n\n#### \_\n\n2009 – 2011\n\nStivichall Primary School\nRECEPTION – YEAR 3\n"
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Contact
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
    text: |
      (this doesnt work)
---
