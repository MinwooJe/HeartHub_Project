# Uncomment the next line to define a global platform for your project
platform :ios, '14.0'

target 'HeartHub' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!


pod 'FSCalendar'
pod 'SnapKit'
pod 'Then'


post_install do |installer|
    installer.pods_project.targets.each do |target|
      target.build_configurations.each do |config|
        config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '14.0'
      end
    end
  end

  # Pods for HeartHub

end
