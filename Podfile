xcodeproj 'SignalR.Client.ObjC/SignalR.Client.ObjC'
workspace 'SignalR.Client.ObjC'

target :"SignalR.Client.iOS", :exclusive => true do
  platform :ios, '6.0'
  pod 'AFNetworking', '2.2.3'
  pod 'SocketRocket', '0.4'
end

target :"SignalR.Client.OSX", :exclusive => true do
  platform :osx, '10.8'
  pod 'AFNetworking', '2.2.3'
  pod 'SocketRocket', '0.4'
end

target :"SignalR.Client.Tests.OSX", :exclusive => true do
    platform :osx, '10.8'
    pod 'OCMock'
end

target :"SignalR.Client.Tests.iOS", :exclusive => true do
    platform :ios, '6.0'
    pod 'OCMock'
end


target :"SignalR.Samples.iOS", :exclusive => true do
  platform :ios, '6.0'
end


target :"SignalR.Samples.OSX", :exclusive => true do
  platform :osx, '10.8'
end
