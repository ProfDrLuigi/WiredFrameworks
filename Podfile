source 'https://github.com/CocoaPods/Specs.git'
use_frameworks!
platform :osx, '10.13'

target 'WiredNetworking' do
    pod 'OpenSSL-Universal'
end

target 'libwired-osx' do
   pod 'OpenSSL-Universal'
end

target 'WiredFoundation' do
   pod 'RegexKitLite'
end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        if target.name == 'RegexKitLite'
            target.build_configurations.each do |config|
                config.build_settings['MACOSX_DEPLOYMENT_TARGET'] = '10.13'
            end
        end
    end
end
