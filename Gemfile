# Public sample: customers run it, so the source stays public (nora needs a token). Maestra machines and CI
# go through nora with a mirror: bundle config set --global mirror.https://rubygems.org https://packages.maestra.io/gems/
# plus BUNDLE_PACKAGES__MAESTRA__IO="token:<nra_ token>" (issues-maestra#1649).
source 'https://rubygems.org'

# You may use http://rbenv.org/ or https://rvm.io/ to install and use this version
ruby ">= 3.1.0"

# Exclude problematic versions of cocoapods and activesupport that causes build failures.
gem 'cocoapods', '>= 1.13', '!= 1.15.0', '!= 1.15.1'
gem 'activesupport', '>= 7.2.3.1'
gem 'xcodeproj', '< 1.26.0'
gem 'concurrent-ruby', '>= 1.3.7'
