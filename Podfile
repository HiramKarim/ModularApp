# Uncomment the next line to define a global platform for your project
# platform :ios, '12.2'

workspace 'AppModular'

# Core Module

def core_pods
    pod 'RxSwift'
end

target 'Core' do
   project 'Core/Core.project'
   core_pods
end

# Application

def application_pods
    core_pods
end

target 'Application' do
    project 'Application/Application.project'
    application_pods
end
