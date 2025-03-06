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
    text: "Networking & IT Infrastructure\n\n\t•\tExperience with modern Cisco equipment, Cisco IOS, OSPFv2, router and switch configuration\n\n\t•\tExperience with modern HPE networking equipment, Aruba Gateways, AOS-S, AOS-CX and Comware based switches, ArubaOS 8 & 10 Access Points, routing protocols, and modern cloud-based network configuration\n\n\t•\tPractical lab skills including Linux, firewall configurations, Windows directories/domains, certificate authorities, and remote VDI\n\n\t•\tExpertise in cutting-edge network technologies (WiFi 7, Private 5G, SD-WAN)\n\n\t•\tProficiency in cloud networking: deploying and managing solutions on Oracle Cloud, Google Cloud, and AWS\n\n\t•\tSystem administration: deploying, configuring, and maintaining enterprise server and infrastructure equipment\n\n\t•\tExperience in network auditing, upgrading IT systems, and network automation using tools such as Ansible and Terraform\n\n\n\nProgramming & Automation\n\n\t•\tStrong Python background (from early education to university), with secure coding practices and automation projects (e.g., smart home systems)\n\n\t•\tFamiliarity with C and C++\n\n\t•\tApplication of programming skills to network automation and infrastructure deployment\n\n\nCommunication & Project Management\n\n\t•\tClient interaction and project scoping to design and deliver tailored network solutions\n\n\t•\tExperience in managing projects from initial design through post-implementation reviews\n\n\t•\tInvolvement in sales efforts and client-facing demonstrations, including working with channel organisations\n\n\nPractical & Technical Abilities\n\n\t•\tHands-on skills demonstrated through personal projects (e.g., designing, fabricating, and painting wooden planters; exterior painting projects)\n\n\t•\tTechnical theatre experience: lighting design, sound operations, and technical management for productions and freelance work\n\n\n\nLanguage Skills\n\n\t•\tProficiency in French (studied since a young age and practiced in real-world settings)\n\n\n\n\n"
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
    colors: colors-d
    variant: variant-b
    title: Education
    subtitle: The section subtitle
    text: "## GCSE GRADES:\n\n10 GCSEs, including Maths and English at Grade 7\n\n## A LEVEL GRADES:\n\nOCR Computer Science: A\n\nOCR Mathematics: C\n\nAQA French: D\n\n## Education\n\n\\###2022 – Present\n\nDe Montfort University – Computer Networks and Security (BSc)\n\n\n\t•\tPursued a BSc in Computer Networks and Security blending networks, security, and programming\n\n\t•\tCompleted specialised Cisco-aligned networking modules covering various Cisco certifications\n\n\t•\tGained practical experience through state-of-the-art labs designed in collaboration with Cisco\n\n\t•\tEnhanced skills in secure coding, network development, and cyber security through lectures, seminars, and lab work\n\n\t•\tPrepared for diverse roles in the field of computer networks and security\n\n\\###2011 – 2022\nKing Henry VIII School\nYEAR 4 – YEAR 11 \n\_\n\\###2009 – 2011\nStivichall Primary School\nRECEPTION – YEAR 3\n"
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
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects and more links
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Links
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
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
