 platform :ios, '9.0'

target 'Clima' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Clima
pod 'SwiftyJSON'
pod 'Alamofire'
pod 'SVProgressHUD'

end
post_install do |installer|
installer.pods_project.targets.each do |target|
target.build_configurations.each do |config|
config.build_settings['SWIFT_VERSION'] = '3.0'
config.build_settings['MACOSX_DEPLOYMENT_TARGET'] = '10.10'
end
end
end
