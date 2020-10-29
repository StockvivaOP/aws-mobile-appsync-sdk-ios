platform :ios, "9.0"

use_frameworks!
inhibit_all_warnings!

AWS_SDK_VERSION = "2.13.0"

target "AWSAppSync" do
  pod "AWSCore", "~> #{AWS_SDK_VERSION}"
  pod "SQLite.swift", "~> 0.12.2"
  pod "ReachabilitySwift", "~> 5.0.0"
  #pod "AppSyncRealTimeClient", :git => "https://github.com/StockvivaOP/aws-appsync-realtime-client-ios.git", :branch => "feature/SVAppsyncRealtimeClientSwiftSDK"
  pod "AppSyncRealTimeClient", :git => "https://github.com/StockvivaOP/aws-appsync-realtime-client-ios.git", :branch => "feature/SV_Sprint_44_2"

  pod "SwiftLint"
end

target "AWSAppSyncTestCommon" do
  pod "AWSS3", "~> #{AWS_SDK_VERSION}"
  pod "ReachabilitySwift", "~> 5.0.0"
  # We directly access a database connection to verify certain initialization
  # setups
  pod "SQLite.swift", "~> 0.12.2"
  #pod "AppSyncRealTimeClient", :git => "https://github.com/StockvivaOP/aws-appsync-realtime-client-ios.git", :branch => "feature/SVAppsyncRealtimeClientSwiftSDK"
  pod "AppSyncRealTimeClient", :git => "https://github.com/StockvivaOP/aws-appsync-realtime-client-ios.git", :branch => "feature/SV_Sprint_44_2"
end

target "AWSAppSyncTestApp" do
  pod "AWSS3", "~> #{AWS_SDK_VERSION}"
  pod "AWSMobileClient", "~> #{AWS_SDK_VERSION}"
end

target "AWSAppSyncTestHostApp" do
end

target "AWSAppSyncUnitTests" do
end

target "AWSAppSyncIntegrationTests" do
end

target "ApolloTests" do
  pod "AWSCore", "~> #{AWS_SDK_VERSION}"
end
