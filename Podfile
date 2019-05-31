platform:ios, '7.0'

inhibit_all_warnings!


target 'AXWebViewController' do
    pod 'AXNavigationBackItemInjection'
    pod 'NJKWebViewProgress'
    pod 'Aspects'
    pod 'AXPracticalHUD'
    
    post_install do |installer|
      installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
          config.build_settings['COMPILER_INDEX_STORE_ENABLE'] = "NO"
        end
      end
    end
   
end


