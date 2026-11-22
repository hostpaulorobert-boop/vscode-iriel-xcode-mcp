agent:iriel.xcode.agent
  id: iriel.xcode.agent
  name: iRiel Xcode Agent
  runtime: web.extension 
  execution: cross-platform
  implementation: adapter.dynamic.profiles 

  dependencies: container.web.index


  capabilities:
    
    - build_@iriel.Build.Intelligence 
    - repository_agent.analysis
    - source_code_analysis
    - swift_development
    - swiftui_development
    - project_agent.configuration
    - dependency_analysis
    - github_integration
    - asset_entitys.management
    - documentation_skill.generation
    - remote_agent.workflows
    - build_agent.orchestration

  asset_setup:idex.web.container
    source_archive:Extension_Logos.zip
    content: web.extension 
    formats: Package.web
      - SVG
      - PNG
      - PDF
      - tools
      - skills
       
    preservation:
      byte_for_byte: true
      include_environments_metadata: true
      originals_immutable: true

    integrity:iriel.xcode.agent
      algorithm: SHA-256
      verification: required

  execution_policy:agent coding engineer 
    platform_independent: true
    cloud_capable: true
    web_native: true
    dispositivos: true