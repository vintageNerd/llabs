---

---


# dump primeiro jekyll

```
[vint@generd ~/30_git/llabs ] $ bundle exec jrkyll serve --livereload
bundler: command not found: jrkyll
Install missing gem executables with `bundle install`
[vint@generd ~/30_git/llabs ] $ bundle install
Fetching gem metadata from https://rubygems.org/...........
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies....
Using concurrent-ruby 1.1.7
Following files may not be writable, so sudo is needed:
  /usr/bin
  /usr/lib/ruby/gems/2.7.0
  /usr/lib/ruby/gems/2.7.0/bin
  /usr/lib/ruby/gems/2.7.0/build_info
  /usr/lib/ruby/gems/2.7.0/cache
  /usr/lib/ruby/gems/2.7.0/doc
  /usr/lib/ruby/gems/2.7.0/extensions
  /usr/lib/ruby/gems/2.7.0/gems
  /usr/lib/ruby/gems/2.7.0/specifications
Using i18n 0.9.5
Using multi_json 1.15.0
Using activesupport 3.2.22.5
Using public_suffix 3.1.1
Using addressable 2.7.0
Fetching json 2.5.1


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle install --path vendor/bundle

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password: 
Enganou-se, tente de novo.


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle install --path vendor/bundle

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password: 
[vint@generd ~/30_git/llabs ] $ 
[vint@generd ~/30_git/llabs ] $ sudo: 1 tentativa incorrecta
^C
[vint@generd ~/30_git/llabs ] $ ^C
[vint@generd ~/30_git/llabs ] $ ^C
[vint@generd ~/30_git/llabs ] $ bundle install --path vendor/bundle
[DEPRECATED] The `--path` flag is deprecated because it relies on being remembered across bundler invocations, which bundler will no longer do in future versions. Instead please use `bundle config set path 'vendor/bundle'`, and stop using this flag
Fetching gem metadata from https://rubygems.org/...........
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies.....
Fetching concurrent-ruby 1.1.7
Installing concurrent-ruby 1.1.7
Fetching i18n 0.9.5
Installing i18n 0.9.5
Fetching multi_json 1.15.0
Installing multi_json 1.15.0
Fetching activesupport 3.2.22.5
Installing activesupport 3.2.22.5
Fetching public_suffix 3.1.1
Installing public_suffix 3.1.1
Fetching addressable 2.7.0
Installing addressable 2.7.0
Fetching json 2.5.1
Installing json 2.5.1 with native extensions
Fetching mini_portile2 2.4.0
Installing mini_portile2 2.4.0
Fetching nokogiri 1.10.10
Installing nokogiri 1.10.10 with native extensions
Fetching algolia_html_extractor 2.6.2
Installing algolia_html_extractor 2.6.2
Fetching httpclient 2.8.3
Installing httpclient 2.8.3
Fetching algoliasearch 1.27.5
Installing algoliasearch 1.27.5
Using bundler 2.1.4
Fetching coffee-script-source 1.11.1
Installing coffee-script-source 1.11.1
Fetching execjs 2.7.0
Installing execjs 2.7.0
Fetching coffee-script 2.4.1
Installing coffee-script 2.4.1
Fetching colorator 1.1.0
Installing colorator 1.1.0
Fetching ruby-enum 0.8.0
Installing ruby-enum 0.8.0
Fetching commonmarker 0.17.13
Installing commonmarker 0.17.13 with native extensions
Fetching unf_ext 0.0.7.7
Installing unf_ext 0.0.7.7 with native extensions
Fetching unf 0.1.4
Installing unf 0.1.4
Fetching simpleidn 0.1.1
Installing simpleidn 0.1.1
Fetching dnsruby 1.61.5
Installing dnsruby 1.61.5
Fetching eventmachine 1.2.7
Installing eventmachine 1.2.7 with native extensions
Fetching http_parser.rb 0.6.0
Installing http_parser.rb 0.6.0 with native extensions
Fetching em-websocket 0.5.2
Installing em-websocket 0.5.2
Fetching ffi 1.14.2
Installing ffi 1.14.2 with native extensions
Fetching ethon 0.12.0
Installing ethon 0.12.0
Fetching faraday-net_http 1.0.0
Installing faraday-net_http 1.0.0
Fetching multipart-post 2.1.1
Installing multipart-post 2.1.1
Fetching ruby2_keywords 0.0.2
Installing ruby2_keywords 0.0.2
Fetching faraday 1.3.0
Installing faraday 1.3.0
Fetching filesize 0.2.0
Installing filesize 0.2.0
Fetching forwardable-extended 2.6.0
Installing forwardable-extended 2.6.0
Fetching gemoji 3.0.1
Installing gemoji 3.0.1
Fetching sawyer 0.8.2
Installing sawyer 0.8.2
Fetching octokit 4.20.0
Installing octokit 4.20.0
Fetching typhoeus 1.4.0
Installing typhoeus 1.4.0
Fetching github-pages-health-check 1.16.1
Installing github-pages-health-check 1.16.1
Fetching rb-fsevent 0.10.4
Installing rb-fsevent 0.10.4
Fetching rb-inotify 0.10.1
Installing rb-inotify 0.10.1
Fetching sass-listen 4.0.0
Installing sass-listen 4.0.0
Fetching sass 3.7.4
Installing sass 3.7.4
Fetching jekyll-sass-converter 1.5.2
Installing jekyll-sass-converter 1.5.2
Fetching listen 3.4.0
Installing listen 3.4.0
Fetching jekyll-watch 2.2.1
Installing jekyll-watch 2.2.1
Fetching rexml 3.2.4
Installing rexml 3.2.4
Fetching kramdown 2.3.0
Installing kramdown 2.3.0
Fetching liquid 4.0.3
Installing liquid 4.0.3
Fetching mercenary 0.3.6
Installing mercenary 0.3.6
Fetching pathutil 0.16.2
Installing pathutil 0.16.2
Fetching rouge 3.23.0
Installing rouge 3.23.0
Fetching safe_yaml 1.0.5
Installing safe_yaml 1.0.5
Fetching jekyll 3.9.0
Installing jekyll 3.9.0
Fetching jekyll-avatar 0.7.0
Installing jekyll-avatar 0.7.0
Fetching jekyll-coffeescript 1.1.1
Installing jekyll-coffeescript 1.1.1
Fetching jekyll-commonmark 1.3.1
Installing jekyll-commonmark 1.3.1
Fetching jekyll-commonmark-ghpages 0.1.6
Installing jekyll-commonmark-ghpages 0.1.6
Fetching jekyll-default-layout 0.1.4
Installing jekyll-default-layout 0.1.4
Fetching jekyll-feed 0.15.1
Installing jekyll-feed 0.15.1
Fetching jekyll-gist 1.5.0
Installing jekyll-gist 1.5.0
Fetching jekyll-github-metadata 2.13.0
Installing jekyll-github-metadata 2.13.0
Fetching html-pipeline 2.14.0
Installing html-pipeline 2.14.0
Fetching jekyll-mentions 1.6.0
Installing jekyll-mentions 1.6.0
Fetching jekyll-optional-front-matter 0.3.2
Installing jekyll-optional-front-matter 0.3.2
Fetching jekyll-paginate 1.1.0
Installing jekyll-paginate 1.1.0
Fetching jekyll-readme-index 0.3.0
Installing jekyll-readme-index 0.3.0
Fetching jekyll-redirect-from 0.16.0
Installing jekyll-redirect-from 0.16.0
Fetching jekyll-relative-links 0.6.1
Installing jekyll-relative-links 0.6.1
Fetching rubyzip 2.3.0
Installing rubyzip 2.3.0
Fetching jekyll-remote-theme 0.4.2
Installing jekyll-remote-theme 0.4.2
Fetching jekyll-seo-tag 2.6.1
Installing jekyll-seo-tag 2.6.1
Fetching jekyll-sitemap 1.4.0
Installing jekyll-sitemap 1.4.0
Fetching jekyll-swiss 1.0.0
Installing jekyll-swiss 1.0.0
Fetching jekyll-theme-architect 0.1.1
Installing jekyll-theme-architect 0.1.1
Fetching jekyll-theme-cayman 0.1.1
Installing jekyll-theme-cayman 0.1.1
Fetching jekyll-theme-dinky 0.1.1
Installing jekyll-theme-dinky 0.1.1
Fetching jekyll-theme-hacker 0.1.2
Installing jekyll-theme-hacker 0.1.2
Fetching jekyll-theme-leap-day 0.1.1
Installing jekyll-theme-leap-day 0.1.1
Fetching jekyll-theme-merlot 0.1.1
Installing jekyll-theme-merlot 0.1.1
Fetching jekyll-theme-midnight 0.1.1
Installing jekyll-theme-midnight 0.1.1
Fetching jekyll-theme-minimal 0.1.1
Installing jekyll-theme-minimal 0.1.1
Fetching jekyll-theme-modernist 0.1.1
Installing jekyll-theme-modernist 0.1.1
Fetching jekyll-theme-primer 0.5.4
Installing jekyll-theme-primer 0.5.4
Fetching jekyll-theme-slate 0.1.1
Installing jekyll-theme-slate 0.1.1
Fetching jekyll-theme-tactile 0.1.1
Installing jekyll-theme-tactile 0.1.1
Fetching jekyll-theme-time-machine 0.1.1
Installing jekyll-theme-time-machine 0.1.1
Fetching jekyll-titles-from-headings 0.5.3
Installing jekyll-titles-from-headings 0.5.3
Fetching jemoji 0.12.0
Installing jemoji 0.12.0
Fetching kramdown-parser-gfm 1.1.0
Installing kramdown-parser-gfm 1.1.0
Fetching minima 2.5.1
Installing minima 2.5.1
Fetching unicode-display_width 1.7.0
Installing unicode-display_width 1.7.0
Fetching terminal-table 1.8.0
Installing terminal-table 1.8.0
Fetching github-pages 209
Installing github-pages 209
Fetching progressbar 1.11.0
Installing progressbar 1.11.0
Fetching verbal_expressions 0.1.5
Installing verbal_expressions 0.1.5
Fetching jekyll-algolia 1.6.0
Installing jekyll-algolia 1.6.0
Fetching jekyll-include-cache 0.2.1
Installing jekyll-include-cache 0.2.1
Fetching tzinfo 2.0.4
Installing tzinfo 2.0.4
Fetching tzinfo-data 1.2020.6
Installing tzinfo-data 1.2020.6
Bundle complete! 9 Gemfile dependencies, 100 gems now installed.
Bundled gems are installed into `./vendor/bundle`
Post-install message from algoliasearch:
A new major version is available for Algolia! Please now use the https://rubygems.org/gems/algolia gem to get the latest features.
Post-install message from dnsruby:
Installing dnsruby...
  For issues and source code: https://github.com/alexdalitz/dnsruby
  For general discussion (please tell us how you use dnsruby): https://groups.google.com/forum/#!forum/dnsruby
Post-install message from sass:

Ruby Sass has reached end-of-life and should no longer be used.

* If you use Sass as a command-line tool, we recommend using Dart Sass, the new
  primary implementation: https://sass-lang.com/install

* If you use Sass as a plug-in for a Ruby web framework, we recommend using the
  sassc gem: https://github.com/sass/sassc-ruby#readme

* For more details, please refer to the Sass blog:
  https://sass-lang.com/blog/posts/7828841

Post-install message from html-pipeline:
-------------------------------------------------
Thank you for installing html-pipeline!
You must bundle Filter gem dependencies.
See html-pipeline README.md for more details.
https://github.com/jch/html-pipeline#dependencies
-------------------------------------------------
[vint@generd ~/30_git/llabs ] $ 
```

