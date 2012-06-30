#!/usr/bin/env rake
require "bundler/gem_tasks"

desc 'Build and copy chai-jquery asset from submodules into vendor/assets'
task :assets do
  sh 'git submodule update --init'
  mkdir_p 'vendor/assets/javascripts'
  cp 'chai-jquery/chai-jquery.js',  'vendor/assets/javascripts/'
end
