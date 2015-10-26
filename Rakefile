# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/android'
require 'rubygems'
require 'motion-gradle'

begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Hello'
  app.api_version = '19'
  app.gradle do
    dependency 'com.danikula:videocache:2.3.1'
  end
end
