source 'https://rubygems.org'

gem 'danger', :git => 'git@github.com:danger/danger.git', :branch => 'master'
gem 'danger-swiftlint'
gem 'cocoapods', '1.5.3'
gem 'fastlane'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
