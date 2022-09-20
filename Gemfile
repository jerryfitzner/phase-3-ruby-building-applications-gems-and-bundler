# frozen_string_literal: true

source "https://rubygems.org"

gem "rspec"
gem "rest-client"
gem "hashie"
gem "sinatra", "2.0.2"
gem "octokit", "~> 2.0"
gem "awesome_print", git: "git@github.com:awesome-print/awesome_print.git"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

group :test do 
  gem "rspec"
end

group :development do
  gem "pry"
end