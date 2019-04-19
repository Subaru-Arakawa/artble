project 'Artble.xcodeproj'

# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def shared_pods

  pod 'Firebase/Core'
  pod 'FirebaseAuth'
  pod 'Firebase/Firestore'
  pod 'Firebase/Storage'
  pod 'IQKeyboardManagerSwift'
  pod 'Kingfisher', '~> 4.0'
  pod 'CodableFirebase'



end


target 'Artble' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Artble
  
  shared_pods
  pod 'Stripe'
  pod 'Alamofire'

end

target 'ArtbleAdmin' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for ArtbleAdmin
  
  shared_pods
  pod 'CropViewController' 

end
