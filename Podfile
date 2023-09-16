# platform :ios, '9.0'
platform :ios, '16.4'

target 'IceCreamShop' do
  use_frameworks!
  pod 'Alamofire', '4.9.1'

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.1'
    end
  end
end
