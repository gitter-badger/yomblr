platform :ios, '9.0'

target 'yomblr' do
  use_frameworks!
  
  pod 'TMTumblrSDK', git: 'https://github.com/ykws/TMTumblrSDK.git', branch: 'develop'
  pod 'SDWebImage'
  pod 'AKImageCropperView', git: 'https://github.com/ykws/AKImageCropperView.git', branch: 'develop-improve'
  pod 'MBProgressHUD'
  pod 'ChameleonFramework/Swift', :git => 'https://github.com/ViccAlexander/Chameleon.git'
  pod 'Firebase'

  target 'yomblrTests' do
    inherit! :search_paths
  end

  plugin 'cocoapods-keys', {
    :project => 'yomblr',
    :keys => []
  }
end
