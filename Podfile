 # Uncomment this line to define a global platform for your project
platform :ios, '8.0'
# Uncomment this line if you're using Swift
use_frameworks!

target 'Numberpedia' do
	# Parse JSON documents
	pod 'JSONModel'

	# timers with blocks
	pod 'NSTimer-Blocks'

	# color with hex string
	pod 'UIColor_Hex_Swift'
end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0.1'
        end
    end
end