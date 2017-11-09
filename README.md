# SixArm.com » Ruby » <br> Gemfile of gems and descriptions

* Docs: <http://sixarm.com/sixarm_ruby_gemfile/doc>
* Repo: <http://github.com/sixarm/sixarm_ruby_gemfile>
<!--header-shut-->

## Introduction

This is a big Gemfile with various gems we use and recommend.

Take what you need, suggest updates as you can, and when you
do your own Gemfile we recommend specifying your gem versions.

For docs go to <http://sixarm.com/sixarm_ruby_gemfile/doc>

Want to help? We're happy to get pull requests.


## Pltaform gems

To install if a platform matches, please use this syntax:

    install_if -> { RUBY_PLATFORM =~ /darwin/ } do
      gem 'foo'
    end
