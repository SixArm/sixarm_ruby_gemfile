##
#
# Gemfile for our typical projects.
#
# Preconditions on Debian:
#
#   curb:
#
#     apt-get install libcurl4-openssl-dev
#
# Preconditions on all systems:
#
#   CoffeeScript:
#
#     npm install -g coffee-script
#
##

source 'http://rubygems.org'
source 'http://gems.github.com'
ruby '2.2.2'

##
#
# Platform
#
##

## Environment
gem 'dotenv'  # Loads environment variables from `.env` file.
gem 'require_all'  # Simple way to load Ruby code from directories.
gem 'memoist'  # Memoize methods invocation for efficiency.

## Rails
gem 'rails', # Ruby On Rails, our main rapid development framework.
gem 'jquery-rails'  # Connects jQuery JavaScript library to Rails.
gem 'jquery-tmpl-rails'  # jQuery Templates for the Rails asset pipeline.
gem 'turbolinks'  # Fast link following using AJAX and Rails Asset Pipeline.

## Rack
gem 'rack'  # Middleware for web applications in Ruby.
gem 'rack-accept'  # HTTP Accept and Accept Charset, Encoding, and Language.
gem 'rack-cache'  # Rack HTTP caching
gem 'rack-mount'  # Rack middleware router that is stackable, dynamic, and tree-based.
gem 'rack-openid'  # Provides a more HTTPish API around the ruby-openid library.
gem 'rack-protection', '>= 1.5.2'  # Protects against typical web attacks like CSRF and XSS.
gem 'rack-ssl'  # Rack middleware to force SSL/TLS.
gem 'rack-test'  # Small, simple testing API for Rack apps.

## Ruby extensions
gem 'facets'  # Premier collection of extension methods for Ruby. [problem with overriding]
gem 'map'  # A hash with ordering, multiple access, structs and options.
gem 'sixarm_ruby_array_slice', '>= 2.1.2' # Ruby base class extension Array #slice methods.
gem 'sixarm_ruby_blob', '>= 1.0.1'  # Blob of data abstract base class.
gem 'sixarm_ruby_fab', '>= 1.0.2'  # Fabricate sample data suitable for testing.
gem 'sixarm_ruby_hash_more', '>= 1.3.0'  # HashMore class for dynamic hashes.
gem 'sixarm_ruby_math_statistics' '>= 1.2.0' # Simple math stats methods like #sum, #mean, #variance.
gem 'sixarm_ruby_numeric_round', '>= 1.0.2'  # Numeric #round, #floor, #ceil methods with precision.
gem 'sixarm_ruby_person_name', '>= 1.1.0'  # PersonName mixin methods for a person model.
gem 'sixarm_ruby_pro_logger', '>= 2.0.1'  # Custom logger with better information.
gem 'sixarm_ruby_ramp', '>= 4.1.0'  # Ramp gem is a toolkit of Ruby base class extensions.
gem 'sixarm_ruby_range_parse', '>= 1.0.1'  # Range.parse method to convert text to a Range object.
gem 'sixarm_ruby_rexml', '>= 2.1.0'  # REXML core for XML documents, elements, attributes.
gem 'sixarm_ruby_time_stamp', '= 1.1.2'  # Time.stamp method for ISO RFC date and time stamp.
gem 'sixarm_ruby_time_terse', '>= 1.1.0'  # Time.terse method for ISO RFC date and time terse.
gem 'sixarm_ruby_to_id', '>= 1.0.8'  # Convert strings to various kinds of id types and uuid types.
gem 'sixarm_ruby_xml_load', '>= 2.1.0'  # XML#load methods to load documents, elements, attributes.
gem 'sixarm_ruby_xml_strip', '>= 2.1.0'  # XML#strip methods to clean XML & HTML.

##
#
# Authentication & Authorization
#
##

## Warden
gem 'warden'  # Rack authentication framework
gem 'warden-github'  # Warden strategy for OAuth integration with GitHub.
gem 'warden-openid'  # Warden strategy for OpenID.
gem 'warden-hmac-authentication'  # Warden strategy for HMAC for APIs.

## Authentication with Devise + OAuth + OmniAuth
gem 'devise'  # Flexible authentication solution for Rails with Warden.
gem 'devise_invitable'  # An authenticated user can invite another user.
gem 'devise_ldap_authenticatable'  # Lightweight Directory Access Protocol authentication.
gem 'devise_openid_authenticatable'  # OpenID authentication module for Devise using Rack::OpenID
gem 'devise_security_extension'  # Security to expire passwords, validate strength, show captchas, etc.
#gem 'devise_oauth2_providable'  # Adds OAuth2 Provider support to our application. [requires old rack-oauth2]

## Omniauth
gem 'omniauth'  # Rack middleware to authenticate with just about anything. [missing omniauth/password]
gem 'omniauth-twitter'
gem 'omniauth-github'
#gem 'oa-oauth', :require => 'omniauth/oauth'  # OAuth strategies for OmniAuth. [requires old multi_xml]

##
#
# Model-View-Controller
#
##

## Models
gem 'activeuuid'  # Add binary (not string) UUIDs to ActiveRecord in MySQL.
gem 'acts_as_list'  # ActiveRecord sorting and reordering based on a position field.
gem 'auto_strip_attributes'  # Helps to remove unnecessary whitespaces from model attributes.
gem 'awesome_nested_set'  # ActiveRecord nested set implemenation with left, parent, right.
#gem 'acts_as_archive'  # Don't delete a record, move it to a different table. [problem with YAML]
gem 'acts-as-taggable-on'  # Tagging plugin with custom tags along dynamic contexts.
gem 'acts_as_singleton'  # Lightweight singleton library for Active Record models.
gem 'attribute_normalizer'  # Normalize attributes cleanly with code blocks and methods.
#gem 'after_commit'  # Callback to trigger methods only after an entire transaction completes. [problem with ActiveRecord]
gem 'dirty-memoize'  # Like Memoize, but designed for mutable and parametizable objects.
gem 'draper'  # Decorator pattern for domain models, to replace typical helpers.
gem 'enumerated_attribute'  # Easy enum for your models, objects and views.
gem 'pacecar'  # Generated scopes for ActiveRecord classes.
gem 'paper_trail'  # Generic versioning library for ActiveRecord.
gem 'polyamorous'  # Extends ActiveRecord with polymorphic belongs_to associations.
gem 'sixarm_ruby_person_name'  # PersonName mixin methods for a users model.

## Views
#gem 'event_calendar'  # Render a calendar HTML view. [problem with undefined method id]
gem 'high_voltage'  # Easily include static pages in your Rails app.
gem 'meta-tags', '>= 2.0.0', '< 3', :require => 'meta_tags',  # Add Search Engine Optimization (SEO) tags to Rails views.
gem 'show_for'  # Wrap your objects with a helper to easily show them.
gem 'simple_form'  # Forms made easy for Rails using a simple DSL and without markup.

## Controlers
gem 'activeadmin', :require => 'sass-rails'  # Admistration framework.
gem 'arel'  # Arel is a SQL Abstract Syntax Tree (AST) manager for Ruby.
gem 'cancan'  # Simple authorization solution for Rails decoupled from roles.
#gem 'carrierwave'  #  Easy uploads for Ruby apps locally, and remotely with Fog. [superceded by refile]
gem 'configatron'  #  Simple and feature rich configuration system for Ruby apps.
gem 'dynamic_form'  # Helpers to deal with model-backed forms in Rails3.
gem 'has_scope'  # Maps controller filters to your resource scopes.
gem 'kaminari'  # Paginator for Rails 3 that is scope & engine based.
gem 'meta_search' # Create simple search forms to be created for ActiveRecord models.
gem 'refile'  # Ruby file uploads; replaces carrierwave.
gem 'responders'  # Rails 3 responders to dry up your application.
gem 'responds_to_parent'  # Controller responds to the parent document of a page.
gem 'settingslogic'  # Simple configuration using ERB, YAML, and Singleton pattern.
gem 'simple-navigation'  # Creating navigation links, tabs, breadcrumbs, etc.
gem 'TextTractor'  # Web interface for clients to edit copy on their websites.

## Sanitize
gem 'sanitize' # Sanitize is a whitelist-based HTML sanitizer.
gem 'acts_as_sanitiled'  # Textiles and sanitizes columns to your specification.
gem 'sanitize-url'  # Accepts a URL and returns one with JavaScript removed.
gem 'sanitized_attributes'  # Automatic sanitization of incoming data for Ruby and Rails.
#gem 'rack-sanitize'  # Remove malicious HTML from requests before it reaches our app. [needs older sanitize]

##
#
# Data
#
##

## Databases
gem 'cassandra'  # Ruby connection to Cassandra distributed database. [interferes with ActiveSupport]
gem 'cube-ruby', require: 'cube'  # Time series data collection & analysis.
gem 'memcached'  # Ruby interface to the libmemcached C client.
gem 'mongo', MONGO_VERSION = '1.9.1'  # Ruby driver for MongoDB, the key-value database.
gem 'mysql2'  # Ruby client library for MySQL relational database.
gem 'pg'  # Ruby client library for PostgreSQL relational database.
gem 'redis'  # Ruby client library for the Redis key value storage engine.
gem 'redis-objects'  # Maps Redis types directly to Ruby objects
gem 'mock_redis', :group => :test  # Provides similar interface as redis-rb but with data in memory.
gem 'redis-namespace'  # Adds a Redis::Namespace class to namespace Redis keys.
gem 'sqlite3'  # Temporary lightweight database especially for testing.

## Databases + ActiveRecord
#gem 'activerecord-postgres-hstore'  # ActiveRecord can use Postgres hstore fast hash storage.
#gem 'activerecord-postgres-array'  # ActiveRecord can use Postgres arrays

## Seeds
gem 'seedbank'  # Structure seed data for database content setup.

## Queues
gem 'amqp'  # Advanced Message Queuing Protocol open standard for messaging middleware.
gem 'dalli'  # High performance memcached client for Ruby.
gem 'delayed_job'  # Background job queue for ActiveRecord backed by Rails database.
gem 'resque'  # Background job queue backed by Redis, especially good for scale.
gem 'resque-scheduler'  # Lightweight job scheduling system built on top of Resque.
#gem 'starling'  # Lightweight persistent queue via memcached protocol. [requires older eventmachine]

## Search
gem 'maxixe'  # Simple statistical segmenter for any language; implements TANGO.
gem 'raspell'  # Ruby binding for the Aspell spelling checker.
gem 'ruby-stemmer', :require => 'lingua/stemmer' # Word stems with libstemmer_c SnowBall.
gem 'rsolr'  # Simple extensible library for working with Solr search.
gem 'sunspot'  # Search using RSolr, Solr search platform, and Lucene search engine.
gem 'ransack'  # Creates search forms for application models.
gem 'thinking-sphinx'  # Ruby connector between ActiveRecord and Sphinx search engine. [*native]

## Files
gem 'archive-tar-minitar'  # Library and tool for POSIX tar archive files.
gem 'file-tail'  # Library to tail files in Ruby.
gem 'fssm'  # File System State Monitor fires events on file system changes.
gem 'hike'  # Library for finding files in a set of paths.
gem 'grit'  # Git bindings for reading a git repository.
gem 'logging' # Flexible logging library for Ruby based on Java log4j.
gem 'mime-types'  # Internet media type, aka content-type, for files.
#gem 'polyglot'  # Registers a loader for a file type and filename extension. [problem with jcode]
gem 'rb-inotify'  # Optimized for some systems with FSSM.
gem 'rubyzip'  # Module to read and write zip files.

############################################################################

## Commands
gem 'command_line_reporter'  # Provides easy formatting for ruby command line output.
gem 'cri'  # Builds easy-to-use commandline interfaces with support for subcommands.

## Communication
gem 'msgpack'  # Binary-based efficient data interchange format.
gem 'net-ssh'  # Net::SSH: a pure-Ruby implementation of the SSH2 client protocol.
gem 'net_dav'  # Net::DAV is a Ruby WebDAV client library in the style of Net::HTTP.
gem 'packetfu'  # Mid-level packet manipulation library for Ruby.
#gem 'thrift_client'  # Client wrapper to encapsulate common failover behavior. [interferes with ActiveSupport]
gem 'vpim'  # vCard and iCalendar support for exchange of contact information and calendars.

## CSS
gem 'bourbon'  # Comprehensive Sass mixins using SCSS syntax for all modern browsers.
gem 'compass'  # Stylesheet framework to streamline CSS creation and maintainance.
gem 'flutie'  # Basic default styles for rails applications.
gem 'sass'  # Extends CSS with nested rules, variables, mixins, selectors, and more.

## Document Generation
gem 'prawn'  # PDF generator.
gem 'rghost'  # Ruby Ghostscript Engine is a document creation and conversion API.

## Encryption
gem 'bcrypt'  # Secure algorithm for hashing passwords, native version.
gem 'bcrypt-ruby'  # Secure algorithm for hashing passwords, pure ruby version.
gem 'encryptor'  # Wrapper for the standard ruby OpenSSL library.
gem 'pbkdf2'  # Password Based Key Derivation Function 2 (PBKDF2)
gem 'scrypt'  # Passwords more secure against hardware brute-force attacks than PBKDF2 or bcrypt.

# Grep
gem 'coypond'  # Semantic grep search for Ruby source code.
gem 'object_regex'  # Regex searching on arrays of arbitrary Ruby objects.

# Images
gem 'easy_captcha'  # Simple captcha image generation for Rails 3 based on rmagick.
gem 'recaptcha'  # ReCaptcha helpers for ruby apps.
gem 'mini_magick'  # Manipulate images via ImageMagick and GraphicsMagick.
gem 'rmagick'  # Interface between Ruby and ImageMagick graphics library.

# Internationalization
gem 'i18n'  # Internationalization and localization solution.
gem 'i18n_routing'  # Translate Rails routes with ease.

##
#
# JavaScript
#
##

## Coffee
gem 'coffee-script'  # Ruby bridge to the JS CoffeeScript compiler.
gem 'coffee-script-source'  # Good looking language that compiles into JavaScript.

## Runners
gem 'execjs'  # Executes JavaScript code from within Ruby.
gem 'libv8'  # Distributes the V8 JavaScript engine in binary and source forms.
gem 'therubyracer'  # Embed the V8 Javascript Interpreter into Ruby.

## JSON: JavaScript Object Notation
gem 'json'  # JSON implementation as a Ruby extension in C.
gem 'json_pure'  # JSON implementation in pure Ruby.
gem 'multi_json'  # Swappable JSON backends utilizing Yajl::Ruby, the JSON gem, JSON pure, etc.
gem 'yajl-ruby'  # JSON implemenations as Ruby C bindings to the Yajl JSON stream library.

## BSON: Binary JSON
gem 'bson', MONGO_VERSION  # Ruby Binary JSON serializtion.
gem 'bson_ext', MONGO_VERSION  # C extensions to accelerate Binary JSON serialization.

############################################################################

# Math
gem 'extendmatrix'  # Enhancements to the Ruby "Vector" and "Matrix" modules.
gem 'gsl'  # GNU Scientific Library (GSL) for numerical computing; requires native libs.
gem 'distribution'  # Statistical distributions multi library wrapper.
gem 'statsample'  # Statistical library for Ruby; modules for descriptive and inferencial stats.
gem 'statsample-optimization'  # Optimization packages for statsample.
gem 'statistics'  # An ActiveRecord gem that makes it easier to do reporting.

# Markup + Parsing
gem 'builder'  # Facilitates structured data like XML markup and events.
gem 'haml'  # HTML Abstraction Markup Language for writing elegant documents.
gem 'happymapper'  # XML to object mapping library.
gem 'hippo'  # Simple DSL to generate and parse HIPAA transaction sets.
gem 'htmlentities'  # Encode/decode HTML & XML named and numerical entities.
gem 'libxml-ruby'  # Ruby language bindings for the GNOME Libxml2 toolkit.
gem 'libxslt-ruby'  #  Ruby language bindings for the GNOME Libxslt toolkit.
gem 'nokogiri'  # Parser for HTML, XML, SAX, and Reader with XPath and CSS selectors.
gem 'ParseTree'  # Extracts the parse tree for Ruby code and returns a sexp.
gem 'prism'  # Microformat parser and HTML toolkit powered by Nokogiri.
gem 'psych'  # A libyaml wrapper for Ruby with native libraries.
gem 'rabl'  # Ruby API Builder Language templating with json, bson, xml, plist, msgpack.
gem 'redcarpet'  # Markdown interpreter in Ruby with speed and safety.
gem 'representative'  # XML/JSON representations of your Ruby objects.
gem 'representative_view'  # Integrate Representative as an ActionView template format.
gem 'ROXML'  # Binding XML and Ruby classes, bidirectionally.
gem 'ruby_parser'  # Ruby parser written in pure ruby.
gem 'ruby-xslt'  # Simple XSLT class based on libxml and libxslt
gem 'sax-machine'  # Simple API for XML for sequential access stream parsing XML.
gem 'tilt'  # Generic interface to multiple Ruby template engines.
gem 'treetop'  # Text parsing and interpretation DSL.
gem 'unicode_utils'  # Unicode utilties for UTF strings and characters.
gem 'xpath'  # DSL for generating XPath expressions.
gem 'yamler'  # YAML helpers for loading ERB, merging, etc.

# State
gem 'aasm'  # Finite state machines, events and transitions for Ruby classes.
gem 'state_machine'  # Creating state machines for attributes on any Ruby class.

# Money
gem 'cashrb'  # Work with Money/Currency without the hassle of Floats; phases out 'money'.
gem 'eu_central_bank'  # Calculate exchange rates from European Central Bank.
gem 'google_currency'  # Ruby Money::Bank interface for the Google Currency exchange data.
gem 'money'  # Library for dealing with money and currency conversion; phased out by 'cashrb'.

# Split Tests
gem 'split', :require => 'redis'  # A/B split test views, Rack-based, Redis-backed.
gem 'vanity'  # Experiment Driven Development framework for Rails.

# System
gem 'childprocess'  #  Controls external programs running in the background.
gem 'daemons'  # Wraps a ruby script to run as a daemon with start/stop/etc.
gem 'ffi'  # Foreign Function Interface enables calling external libraries.
gem 'RubyInline'  #  Enables us to write foreign code within our Ruby code.
gem 'whenever'  # Cron job wrapper for writing and deploying timed jobs.

# Time
gem 'american_date'  # Parse dates using U.S. style month/day/year format.
gem 'chronic' # Natural language parser for dates and times.
gem 'chronic_duration' # Natural language parser for durations.
gem 'holidays'  # Ruby methods to deal with dates for holidays.
gem 'tzinfo'  # Daylight-savings timezone library.

# Video
gem 'rvideo'  # Inspect and process video or audio files.
gem 'ffmpeg-ruby'  # FFMpeg Ruby Bridge. Call FFMpeg/LibAVCodec/LibAVFormat.

# Visualization
gem 'gruff'  # Beautiful easy graphs for datasets.
gem 'protovis-rails' # Protovis Javascript graphing library for Rails 3.1.
gem 'seer'  # Wrapper for the Google Visualization API.
gem 'rails-erd'  # Entity-Relationship Diagrams for Rails.
gem 'railroady'  # Rails 3 model and controller UML diagramming using graphviz.
gem 'rubyvis' 	 # Ruby port of Stanford Protovis library.
gem 'sparklines'  # Tiny graphs especially good for displaying inline data.
gem 'svg-graph'  # SVG:::Graph is a pure Ruby library for generating charts.

# HTTP & REST
gem 'browser'  # Do some browser detection with Ruby, and includes ActionController integration.
#gem 'cramp'  # Fully asynchronous IO built on top of EventMachine for many connections. [requires Rails 3.0]
gem 'curb'  # Ruby-language bindings for curl's library to do client-side URL transfer.
gem 'em-http-request'  # Async HTTP Request client based on EventMachine.
gem 'eventmachine'  # Event driven i/o for network communications and web interaction.
gem 'excon'  # EXtended http(s) CONnections.
gem 'httparty'  # HTTP client library for consuming restful web services.
gem 'mechanize'  # Automating interaction with websites.
gem 'rest-client'  # Simple DSL for accessing HTTP and REST resources.
gem 'typhoeus'  # Runs HTTP requests in parallel.
gem 'weary'  # A little DSL for consuming RESTful web services.
gem 'wrest'  # Ruby HTTP/REST client with caching, backends, and async EventMachine calls.

# Chat
#gem 'blather'  # XMPP/Jabber Library and DSL on EventMachine and Nokogiri. [syntax error]
gem 'cinch'  # IRC Bot Building Framework.
gem 'jabber-bot'  #  Create simple regex powered Jabber bots.
gem 'jabber-tee'  #  Utility to sending messages to a jabber server and console.
#gem 'xmpp4r'  # XMPP/Jabber library for Ruby. [syntax error]
gem 'xmpp4r-simple'  # Jabber::Simple - easy-to-use Jabber client library. [syntax error]

# Geocoding
#gem 'acts_as_geocodable'  # Rails plugin that makes your applications geo-aware. [interferes with ActiveRecord]
gem 'geocoder'  # Geocoding by street or IP address, reverse geocoding, distance queries.
gem 'graticule'  # Geocoding API for address coordinates, distance calculations, and many APIs.
gem 'ipgeolocation'  # Remote, IP-Based Geolocation with 3 services as 1-liners.

# Mail
gem 'larch'  # Copies messages from one IMAP server to another.
gem 'mail'  # Ruby mail handler for email generation, parsing, and sending.
gem 'mail_form'  # Send e-mail from Rails forms with I18n, naming, validations, attachments. and request info.
gem 'maildir' # Read and write arbitrary messages in DJB's maildir format.
gem 'maildir-queue' # Simple queue API with a maildir backend, plus HTTP API.
gem 'mailman'  # Incoming mail processing microframework for POP3, Maildir, and Rails.
gem 'markerb'  # Multipart email templates made easy with Markdown + ERb.

# Vitals
gem 'airbrake'  # Send application errors to hosted service; formerly Hoptoad.
gem 'exception_notification', :require => 'exception_notifier'  # Email us any Ruby exception.
gem 'hitimes'  # Fast, high resolution timer library for recording performance metrics.
gem 'npm'  # New Relic RPM Ruby Agent.
gem 'query_trace'  # Adds generated SQL statements to the Rails logs to ease debugging.
gem 'rackamole'  # Observe your web applications in the wild.
gem 'rails-footnotes'  # Add diagnostic information to the footer of each Rails page.
gem 'rails_metrics'  # Measurements for your app on top of ActiveSupport::Notifications.

##
#
# API
#
##

## APIs
gem 'active_merchant'  # Simple payment abstraction library by Shopify.
gem 'aws' # Amazon Web Services including EC2, S3, SQS, SimpleDB, etc.
gem 'bliptv' # Blip.tv API for videos and user accounts
#gem 'contacts'  # Grab contacts from Yahoo, AOL, Gmail, Hotmail, Plaxo, etc. [problem with jcode]
gem 'fb_graph'  # A full-stack Facebook Graph API wrapper in Ruby.
#gem 'flickr_fu'  # Flickr API for photo sharing. [problem with xml-magic]
gem 'fog'  # Ruby cloud services for Amazon S3, Rackspace Cloud, Google Storage, etc.
gem 'garb'  # Google Analytics API.
gem 'google-translate' # Google Translate words and phrases among languages.
gem 'googlecharts'  # Google Charts API.
gem 'gravatar_image_tag'  # Rails view helper to show a user thumbnail from Gravatar.
gem 'imdb'  # Internet Movie Database API.
gem 'linkedin'  # LinkedIn API for social networking.
gem 'mixpanel'  # Track events in Mixpanel service via Rack.
gem 'pivotal-tracker'  # Provides ActiveRecord-style interface for the Pivotal Tracker API.
gem 'rapns'  # Apple Push Notification Service with Rails 3.
gem 'tumblr' # Tumblr blog posting API.
gem 'twitter'  # Twitter REST and Search APIs.
gem 'urban'  # Look up definitions in Urban Dictionary.
gem 'vimeo'  # Vimeo video API.
#gem 'wepay-rails'  # WePay API for sending money and purchasing. [needs config file]
gem 'wepredict'  # WePredict data mining API.
gem 'www-delicious'  # Delicious.com bookmarking service API.

## APIs to ticket tracking systems
gem 'ticketmaster'  # API to ticket tracking and project management systems.
gem 'ticketmaster-basecamp'  # API to Basecamp by 37signals at www.basecamphq.com
gem 'ticketmaster-bugzilla'  # API to Bugzilla.
gem 'ticketmaster-codaset'  # API to Codaset.
gem 'ticketmaster-github'  # API to GitHub Issue Tracking at www.github.com
gem 'ticketmaster-kanbanpad'  # API to Kanban Pad.
gem 'ticketmaster-lighthouse'  # API to Lighthouse.
gem 'ticketmaster-pivotal'  # API to Pivotal Tracker.
gem 'ticketmaster-redmine'  # API to Redmine.
gem 'ticketmaster-trac'  # API to Trac.
gem 'ticketmaster-unfuddle'  # API to Unfuddle.

##
#
# Assets
#
##

group :assets do
  gem 'sass-rails', "  ~> 3.1.0"  # Sass adapter for the Rails asset pipeline.
  gem 'coffee-rails', "~> 3.1.0"  # CoffeScript adapter for the Rails asset pipeline.
end

##
#
# Development
#
##

group :development do
  gem 'annotate'  # Annotates Rails code based on the database schema.
  gem 'better_errors', '>= 2.0.0'  # Better error page for Rack apps, with source, REPL, inspection, etc.
  gem 'binding_of_caller', '>= 0.7.2', :platforms=>[:mri_21]  # Retrieve the binding of a method's caller.
  gem 'growl'  # Cross-platform notification sender.
  gem 'haml-rails'  # Provides Haml generators for Rails 3 and templating engine.
  gem 'launchy'  # Start cross-platform applications like a browser or email.
  gem 'libnotify'  # Ruby bindings for libnotify using FFI.
  gem 'rails_layout', '>= 1.0.23'  # Generate Rails application layout files for use with various front-end frameworks.
end

gem :development, :servers do
  gem 'thin'  # Ruby web server that is secure, stable, fast and extensible.
  gem 'puma'
  gem 'unicorn'
end

group :development, :filesystem	do
  gem 'rb-fchange', require: false  # Ruby wrapper for Windows filesystem monitoring.
  gem 'rb-fsevent', require: false  # Ruby wrapper for OSX filesystem monitoring by using FSEvents.
  gem 'rb-inotify', require: false  # Ruby wrapper for Linux filesystem monitoring by using inotify.
end

group :development, :test, :tools do
  gem 'axe'  # Command line utility for parsing Rails log files.
  gem 'itslog'  # Log formatter for Rails 3 with time stamps, colors, formatting, etc.
  gem 'did_you_mean'  # Add suggestions to error messages.
end

group :development, :irb do
  gem 'ansi'  #  ANSI code based colorization and stylization of output.
  gem 'awesome_print'  # Pretty print Ruby objects to visualize their structure
  gem 'bond'  #  Improves autocompletion in ruby, especially for irb/ripl.
  gem 'coderay'  # Fast and easy syntax highlighting for languages.
  gem 'columnize'  # Shows output arranged into columns for easier reading.
  gem 'hijack'  # Provides an irb session to a running ruby process.
  gem 'hirb'  # Mini view framework for console applications.
  gem 'irbtools'  # Meta gem that installs useful irb gems.
  gem 'looksee'  # Supercharged method introspection in IRB
  gem 'racksh'  # Console for any Rack based ruby web app
  gem 'utility_belt'  # IRB power user tools
end

group :development, :ripl do
  gem 'ripl'  # Ruby Interactive Print Loop, a modular alternative to IRB.
  gem 'ripltools'  # A meta gem for ripl plugins.
  gem 'ripl-after_rc'  # Defines blocks to run after ~/.irbrc
  gem 'ripl-auto_indent'  # Indents our entered Ruby code.
  gem 'ripl-color_error'  # Colorize error messages.
  gem 'ripl-color_result'  # Colorize result messages.
  gem 'ripl-color_streams'  # Colorize stdout and stderr.
  gem 'ripl-commands'  # Add RIPL commands similar to IRB.
  gem 'ripl-debug'  # Automatically pass a failed eval to ruby-debug.
  gem 'ripl-fresh'  # Fresh Ruby Enhanced SHell.
  gem 'ripl-hijack'  # Hijacks a running process.
  gem 'ripl-i18n'  # A ripl plugin que habla ta langue.
  gem 'ripl-irb'  # Smoothes the transition from IRB.
  gem 'ripl-multi_line'  # Adds mult-line eval.
  gem 'ripl-play'  # Record and playback inputs in RIPL.
  gem 'ripl-profiles'  # Adds --profile option to load ~/.ripl/profiles.
  gem 'ripl-rack'  # For rack apps.
  gem 'ripl-rails'  # Alternative to Rails' script/console.
  gem 'ripl-rc'  # Plugins collection-- take what we want.
  gem 'ripl-ripper'  # Uses ripper to add multi-linee.
  gem 'ripl-rocket'  #  Rocketize your ripl output.
  gem 'ripl-short_errors'  #  Only show the first backtrace entry of errors.
end

group :development, :pry do
  gem 'pry'  # An IRB alternative and runtime developer console.
  gem 'pry-doc'  # YARD and extended documentation support for Pry.
  gem 'pry-exception_explorer'  # Enter the context of exceptions.
  gem 'pry-nav'  # Turn Pry into a primitive debugger with 'step' and 'next'.
  gem 'pry-stack_explorer'  # Walk the stack in a Pry session.
  gem 'pry-rails'  # Use Pry as your rails console.
end

group :development, :guard do
  gem 'guard'  # Command line tool for file modification events
  gem 'guard-annotate'  # Annotates Rails classes based on the db schema.
  gem 'guard-bundler'  # Installs and updates our gem bundle as needed.
  gem 'guard-chef'  # Uploads Chef roles, cookbooks, and databags.
  gem 'guard-coffeescript'  # Compiles your CoffeeScript files into JavaScript.
  gem 'guard-compass'  # Rebuilds Compass SCSS and SASS files to stylesheets.
  gem 'guard-cucumber'  # Runs Cucumber features, much like autotest.
  gem 'guard-haml'  # Compiles HAML files to HTML.
  gem 'guard-jasmine', '>= 1.18.0'  # Runs Jasmine specs.
  gem 'guard-jasmine-headless-webkit', '>= 0.3.2'  # Runs Jasmine specs using headless WebKit.
  gem 'guard-minitest', '>= 0.5.0'  # Runs MiniTest tests, much like autotest.
  gem 'guard-rails', '>= 0.4.7'  # Restart the Rails development server automatically.
  gem 'guard-rails-assets', '>= 0.1.3' # Compiles Rails 3.x assets.
  gem 'guard-rails_best_practices', '>= 0.1.3'  # Code metric tool for quality of rails code.
  gem 'guard-readme-on-github', '>= 0.0.1'  # Preview your README.md as if it was on github.
  gem 'guard-rspec'  # Runs rspec tests.
  gem 'guard-sass', '>= 1.3.2'  # Compiles SASS files to CSS.
  gem 'guard-spork'  # Manage Spork DRb servers.
  gem 'guard-sprockets', '>= 0.4.2'  # Packages our JavaScript files together.
  gem 'guard-uglify', '>= 0.1.0'  # Compresses our application.js by using uglifyjs.
  gem 'guard-yard', '>= 2.1.3'  #  Run and update the local YARD Documentation Server.
end

group :development, :documentation do
  gem 'bdoc'  # Local gem documentation browser.
  gem 'rdoc'  # Default documentation generation tool for Ruby code. Rails affects the version.
  gem 'sdoc'  # An rdoc generator for html with javascript search index. Rails affects the version.
  gem 'yard'  # Improved documentation generation tool for Ruby code with more features.
end

group :development, :commands do
  gem 'bundler'  # Manages an application's dependencies, such as in a Rails Gemfile.
  #gem 'chef'  # Systems integration framework for configuration management.
  gem 'mixlib-cli'  # A simple mixin for CLI interfaces, including option parsing.
  gem 'mixlib-log'  # A simple mixin for log functionality.
  gem 'mixlib-authentication'  # A simple mixin for per-request authentication.
  gem 'mixlib-config'  # A simple mixin for class-based configurations.
  gem 'rake'  # Scripting framework like Make with tasks, dependencies, and a DSL.
  #gem 'rake-remote_task'  # Extends Rake to run tasks on remote servers. [requires older rake]
  gem 'thor'  # Scripting framework that replaces rake, sake and rubigen.
end

group :development, :vlad do
  gem 'vlad'  # Pragmatic application deployment automation.
  gem 'vlad-git'  # Vlad plugin for git version control.
  gem 'vlad-extras'  # Vlad plugin for assets, symlinks, nginx, node, monit and more.
end

group :development, :debug do
  gem 'linecache19' # Module for reading and caching lines, useful in a debugger.
  gem 'lll'  # Line logger for debugging that displays an expression and its value.
  gem 'rbtrace'  # Shows method calls happening inside ruby processes.
  gem 'ruby_core_source'  # Retrieve Ruby core source files.
  gem 'ruby-prof'  # fast code profiler for Ruby with native C code.
  gem 'rubygems-test'  # Commands for testing gems and reporting results.
  case RUBY_VERSION.to_f
  when 1.8...1.9
    gem 'ruby-debug19'  # Debug Ruby 1.8 by using a command line interface for ruby-debug.
  when 1.9...2.0
    gem 'debugger'  # Debug Ruby 1.9 by using a fast implementation of the standard Ruby debug.rb.
  when 2.0...3.0
    gem 'byebug'  # Debug Ruby 2.0 by using the TracePoint API.
  end
end

##
#
# Test
#
##

group :test, :tdd do
  gem 'database_cleaner'  # Ensures a clean state for testing.
  gem 'diff_matcher'  # Performs recursive matches on values.
  gem 'parallel_tests'  # Run MiniTest + RSpec + Cucumber on multi cores and CPUs.
  gem 'ruby-prof'  # Fast code profiler for Ruby with native C code.
  gem 'spork'  # A forking Drb spec server for faster startup of tests.
  gem 'turn', :require => false  # Test::Unit results show each test on its own line.
  gem 'webrat' # Simulates a browser for testing inside a Ruby process.
  gem 'valid_attribute'  # Minimalist validation BDD for ActiveModel specs.
  gem 'ZenTest'  # Speeds up XP by scanning your target and unit-test code.
end

group :test, :capybara
  gem 'capybara'  # Integration test tool to simulate a user on a website.
  gem 'capybara-webkit'  # Capybara webkit driver for true headless testing.
  gem 'capybara_minitest_spec'  # MiniTest::Spec expectations for Capybara node matchers.
  gem 'capybara-slow_finder_errors'  # Detect Capybara tests that time out.
end

group :test, :minitest do
  gem 'minitest'  # Ruby's core TDD, BDD, mocking, and benchmarking.
  gem 'minitest-bang'  # Provides minitest spec #let! method.
  gem 'minitest-capybara'  #  Add Capybara driver switching parameters to minitest/spec.
  gem 'minitest-reporters'  # Create customizable MiniTest output formats.
  gem 'minitest-matchers'  # RSpec/Shoulda-style matchers for minitest.
  gem 'minitest-metadata'  # Annotate tests with metadata key-value pairs.
  gem 'minitest-spec-rails'  # Drop in MiniTest::Spec support for Rails 3.
  gem 'minitest-reporters'  # Create customizable MiniTest output formats
  gem 'sixarm_ruby_minitest_extensions', '>= 1.0.5'  # Minitest extra methods for common use cases.
end

group :test, :email do
  gem 'action_mailer_cache_delivery'  # Enhance ActionMailer with a :cache delivery method.
  gem 'email_spec'  # RSpec/MiniTest matchers and Cucumber steps for testing email in a Ruby app.
end

group :development, :test, :factories, :minifacture do
  'gem 'minifacture'  # Factory creators in the spirit of minitest.
end

group :development, :test, :factories, :factory_girl do
  gem 'factory_girl'  # Framework and DSL for test factories.
  gem 'factory_girl_rails'  # Integrates Factory Girl and Rails.
end

group :test, :rspec do
  gem 'rspec'  # Behavior Driven Development (BDD) for Ruby
  gem 'rspec-core'  # RSpec runner and example groups.
  gem 'rspec-expectations'  # RSpec matchers for should and should_not.
  gem 'rspec-mocks'  # RSpec test double framework with stubbing and mocking.
  gem 'rspec-rails'  # RSpec version 2.x for Rails version 3.x.
  gem 'shoulda-matchers' # RSpec testing matchers for Rails 3.x.
end

group :test, :jasmine do
  gem 'evergreen', :require => 'evergreen/rails' # Run Jasmine tests in the app.
  gem 'jasmine'  # JavaScript testing framework that is DOM-less.
  gem 'jasmine-headless-webkit'  # Runs Jasmine tests via QtWebKit widget.
end

group :test, :cucumber do
  gem 'aruba'  # Cucumber extension for command line applications.
  gem 'bermuda'  # Cucumber steps for jQuery UI interactions with capybara.
  gem 'cucumber'  # Behavior Driven Development with business-readable DSL.
  gem 'cucumber-rails'  # Cucumber BDD generators and runtime for Rails.
  gem 'gherkin'  # Fast lexer/parser for the Gherkin BDD cucumber syntax.
end

group :test, :capybara do
  gem 'capybara'  # Integration test tool to simulate a user on a website.
  #gem 'capybara-webkit'  # Headless browser for Capybara with WebKit via QtWebKit. [needs older capybara]
  gem 'hermes'  # Utilities for Capybara and ActiveSupport::TestCase.
end

group :test, :selenium do
  gem 'selenium-client'  # Ruby driver for Selenium Remote Control.
  gem 'selenium-rc'  # Selenium Server packaged as a gem
  gem 'selenium-webdriver'  # WebDriver tool for writing automated tests of websites.
end

group :test, :tee do
  gem 'gor'  # Tee HTTP traffic from production to other environments.
end

group :test, :doubles do
  # Local
  gem 'bourne', :require => false  # Extends mocha with spies to track and query our mocks and stubs.
  gem 'forgery'  # Mock data generator for names, places, emails, etc.
  gem 'mocha', :require => false  # Mocking and stubbing library for test doubles for Ruby.
  gem 'rr'  # Test double framework for mocks, stubs, fakes, spies, proxies.
  gem 'timecop'  # Mocks Ruby Time.now, Date.now, DateTime.now for time travel.
  # Remote
  gem 'fakeweb'  # Helper for faking web requests in Ruby at a global level.
  gem 'sham_rack'  # Plumbs HTTP requests into Rack to stub HTTP services.
  gem 'vcr'  # Record and replay your test suite's HTTP interactions.
  gem 'webmock'  # Stubs HTTP requests and setting expectations on HTTP requests.
end

group :test, :extras do
  gem 'merimee', :group => :test, :require => false  # Spellcheck via Wordpress.
end

group :test, :quality do
  gem 'brakeman'  # Detects security vulnerabilities in Rails apps via static analysis.
  gem 'bullet'  # Detects database N+1 queries, unused eager loading, and counter cache needs.
  gem 'cane'  # Code quality threshold checking as part of your build.
  gem 'churn'  # Detects code that changes often for us to review, refactor, retest.
  gem 'coveralls', require: false  # Web service to track code coverage over time.
  gem 'debt_ceiling'  # Scores a technical debt metric and manages debt reduction.
  gem 'flay'  # Analyzes code for structural similarities to find areas for refactoring.
  gem 'flog'  # Scores an ABC complexity metric: Assignments, Branches, Calls.
  gem 'heckle'  # Perturbs our tests to ensure they are working correctly.
  gem 'laser'  # LASER: Lexically- and Semantically-Enriched Ruby bug detector.
  #gem 'metrical'  # Executes MetricFu separate from your project's dependencies. [requires newer metric_fu]
  gem 'metric_fu'  #  Meta-analytics that runs churn, reek, roodi, etc. and graphs results.
  gem 'reek'  # Detects code smells like coupling, clumping, large areas, short names.
  gem 'roodi'  # Ruby Object Oriented Design Inferometer: parses code to warn on design issues.
  #gem 'rails_best_practices'  # parse codes in vendor, spec, test and features directories. [Retired; less-maintained]
  gem 'rubocop'  # Ruby static code analyzer, based on the community Ruby style guide.
  gem 'rubycritic'  # Reporter that wraps gems such as Reek, Flay and Flog.
  gem 'sandi_meter'  # Static analysis tool for checking Ruby code for Sandi Metz' rules.
  gem 'simplecov', require: false  # Code coverage analyzer for Ruby 1.9+
  gem 'simplecov-html', require: false  # HTML output formatter for SimpleCov.
  #gem 'simplecov-rcov-text', require: false  # Text output formatter for SimpleCov. [Outdated]
  gem 'sourcify'  # Workarounds before ruby-core has Proc#to_source & friends.
end


##
#
# To Do
#
##

gem 'wrap'  # Better :before and :after callbacks for any ruby class
gem 'irbcp'  # IRB command "cp" to access to your system's clipboard for copy and paste.
gem 'slug'  # A simple slug library that supports unicode.

# Multi-environment configuration
# gem 'simpleconfig'

# API
# gem 'rabl'

# Performance and Exception management
# gem 'airbrake'
gem 'newrelic_rpm'  # New Relic performance management system.


# Security
# gem 'secure_headers'

# Miscellanea
# gem 'google-analytics-rails'
# gem 'haml'
# gem 'http_accept_language'
gem 'jquery-rails'
gem 'nokogiri'
# gem 'resque', require: 'resque/server' # Resque web interface

# Assets
gem 'coffee-rails', '~> 4.0.0'
gem 'quiet_assets', '>= 1.0.3'  # Turn off Rails asset pipeline log.
# gem 'haml_assets'

# gem 'handlebars_assets'
gem 'i18n-js'
gem 'jquery-turbolinks'
gem 'less-rails'
gem 'sass-rails', '~> 4.0.0'
gem 'therubyracer'
gem 'turbolinks'
gem 'twitter-bootstrap-rails', github: 'diowa/twitter-bootstrap-rails', branch: 'fontawesome-3.2.1'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'debugger'
  gem 'delorean'
  gem 'factory_girl_rails'
  gem 'faker'  # Generate fake data: names, addresses, phone numbers, etc.
  gem 'launchy'  # Launch cross-platform applications such as a web browser, email client, etc.
end

group :development do
  gem 'bullet'
  gem 'meta_request'
end

group :test do
  gem 'capybara'
  gem 'coveralls', require: false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webmock', require: false
end

group :staging, :production do
  gem 'rails_12factor'
end

gem 'sixarm_ruby_blob', '= 1.0.1'  # Track a blob of data such as a image file.
gem 'sixarm_ruby_hash_more'  # Hash of hashes with easy calculations.
gem 'sixarm_ruby_to_id', '= 1.0.8'  # Typecast and santize an object to and id or uuid.

  gem 'codesake-dawn', '>= 1.0.0'  # Static analysis security scanner for Ruby web applications.
  #gem 'simple_mock'  # Fast partial mocking with MiniTest::Mock and SimpleDelegator.
  gem 'sixarm_ruby_fab', '= 1.0.2'  # Fabricate sample data suitable for testing.
  gem 'valid_attribute'  # Minimalist validation BDD for ActiveModel specs.

## Assets
gem 'sprockets'  # Preprocesses and concatenates JavaScript source files.
gem 'uglifier'  # Ruby wrapper for UglifyJS JavaScript compressor.
