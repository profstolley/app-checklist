Technology Checklist

Students who have not successfully completed all of the items on this checklist by Friday, 22 January **must** withdraw from the course.

### Technology Essentials

- [x] Have a non-Windows operating system (OS X, Linux [could be virtualized]). If you choose to complete this course on a Windows computer, the instructor will not be able to help you with any tech issues beyond the contents of your projects' Git repositories.
- [x] If OS X, install XCode from the App Store and Homebrew with [these instructions](http://brew.sh/#install)
- [x] Set up Git on your computer (use Homebrew on OS X, Linux package manager, or compile from source)
- [x] Install a recommended text editor (TextWrangler, BBEdit, or Textmate on Mac; anything that handles Ruby syntax well on your Linux flavor)

### Git & GitHub Basics
- [x] Create a GitHub account
- [x] Create a new Git repo on your computer
- [x] Push the repo and paste its Web URL on GitHub here: (hope this is acceptable, it's one of my repositories from com530) https://github.com/thedanmartin/expanded-web-presence
- [x] On GitHub, fork the GitHub repository for the Technology Checklist
- [x] Clone your Technology Checklist fork to your computer
- [x] Create and checkout a branch with your name, e.g., `git checkout -b karl` (branch is "dpm")
- [x] Manipulate this `README.md` Markdown file & commit the changes
- [x] Push the changes you commit back up to GitHub until you’ve completed the Technology Checklist

### Ruby & Rails Setup
- [x] Install Ruby 2 under RVM; run `ruby -v` and paste the output here:

ontime:app-checklist rachelrolland$ ruby -v
ruby 2.0.0p481 (2014-05-08 revision 45883) [universal.x86_64-darwin14]
ontime:app-checklist rachelrolland$

- [x] Install Rails 4 via `gem install rails`;

ontime:app-checklist rachelrolland$ gem install rails
Fetching: i18n-0.7.0.gem (100%)
ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /Library/Ruby/Gems/2.0.0 directory.
ontime:app-checklist rachelrolland$

^^^Does this mean it's already installed, or do I need to do some additional setup so I have permissions?

run `rails -v` and paste the output here:

ontime:app-checklist rachelrolland$ rails -v
Rails is not currently installed on this system. To get the latest version, simply type:

    $ sudo gem install rails

You can then rerun your "rails" command.
ontime:app-checklist rachelrolland$ sudo gem install rails
Password:
Sorry, try again.
Password:
Fetching: i18n-0.7.0.gem (100%)
Successfully installed i18n-0.7.0
Fetching: thread_safe-0.3.4.gem (100%)
Successfully installed thread_safe-0.3.4
Fetching: tzinfo-1.2.2.gem (100%)
Successfully installed tzinfo-1.2.2
Fetching: minitest-5.5.1.gem (100%)
Successfully installed minitest-5.5.1
Fetching: activesupport-4.2.0.gem (100%)
Successfully installed activesupport-4.2.0
Fetching: rack-1.6.0.gem (100%)
Successfully installed rack-1.6.0
Fetching: rack-test-0.6.3.gem (100%)
Successfully installed rack-test-0.6.3
Fetching: mini_portile-0.6.2.gem (100%)
Successfully installed mini_portile-0.6.2
Fetching: nokogiri-1.6.5.gem (100%)
Building native extensions.  This could take a while...
Successfully installed nokogiri-1.6.5
Fetching: loofah-2.0.1.gem (100%)
Successfully installed loofah-2.0.1
Fetching: rails-html-sanitizer-1.0.1.gem (100%)
Successfully installed rails-html-sanitizer-1.0.1
Fetching: rails-deprecated_sanitizer-1.0.3.gem (100%)
Successfully installed rails-deprecated_sanitizer-1.0.3
Fetching: rails-dom-testing-1.0.5.gem (100%)
Successfully installed rails-dom-testing-1.0.5
Fetching: builder-3.2.2.gem (100%)
Successfully installed builder-3.2.2
Fetching: erubis-2.7.0.gem (100%)
Successfully installed erubis-2.7.0
Fetching: actionview-4.2.0.gem (100%)
Successfully installed actionview-4.2.0
Fetching: actionpack-4.2.0.gem (100%)
Successfully installed actionpack-4.2.0
Fetching: activemodel-4.2.0.gem (100%)
Successfully installed activemodel-4.2.0
Fetching: arel-6.0.0.gem (100%)
Successfully installed arel-6.0.0
Fetching: activerecord-4.2.0.gem (100%)
Successfully installed activerecord-4.2.0
Fetching: globalid-0.3.0.gem (100%)
Successfully installed globalid-0.3.0
Fetching: activejob-4.2.0.gem (100%)
Successfully installed activejob-4.2.0
Fetching: mime-types-2.4.3.gem (100%)
Successfully installed mime-types-2.4.3
Fetching: mail-2.6.3.gem (100%)
Successfully installed mail-2.6.3
Fetching: actionmailer-4.2.0.gem (100%)
Successfully installed actionmailer-4.2.0
Fetching: thor-0.19.1.gem (100%)
Successfully installed thor-0.19.1
Fetching: railties-4.2.0.gem (100%)
railties's executable "rails" conflicts with /usr/bin/rails
Overwrite the executable? [yN]  y
Successfully installed railties-4.2.0
Fetching: bundler-1.7.12.gem (100%)
Successfully installed bundler-1.7.12
Fetching: hike-1.2.3.gem (100%)
Successfully installed hike-1.2.3
Fetching: multi_json-1.10.1.gem (100%)
Successfully installed multi_json-1.10.1
Fetching: tilt-1.4.1.gem (100%)
Successfully installed tilt-1.4.1
Fetching: sprockets-2.12.3.gem (100%)
Successfully installed sprockets-2.12.3
Fetching: sprockets-rails-2.2.2.gem (100%)
Successfully installed sprockets-rails-2.2.2
Fetching: rails-4.2.0.gem (100%)
Successfully installed rails-4.2.0
Parsing documentation for i18n-0.7.0
Installing ri documentation for i18n-0.7.0
Parsing documentation for thread_safe-0.3.4
Installing ri documentation for thread_safe-0.3.4
Parsing documentation for tzinfo-1.2.2
Installing ri documentation for tzinfo-1.2.2
Parsing documentation for minitest-5.5.1
Installing ri documentation for minitest-5.5.1
Parsing documentation for activesupport-4.2.0
unable to convert "\x84" from ASCII-8BIT to UTF-8 for lib/active_support/values/unicode_tables.dat, skipping
Installing ri documentation for activesupport-4.2.0
Parsing documentation for rack-1.6.0
Installing ri documentation for rack-1.6.0
Parsing documentation for rack-test-0.6.3
Installing ri documentation for rack-test-0.6.3
Parsing documentation for mini_portile-0.6.2
Installing ri documentation for mini_portile-0.6.2
Parsing documentation for nokogiri-1.6.5
unable to convert "\xCA" from ASCII-8BIT to UTF-8 for lib/nokogiri/nokogiri.bundle, skipping
Installing ri documentation for nokogiri-1.6.5
Parsing documentation for loofah-2.0.1
Installing ri documentation for loofah-2.0.1
Parsing documentation for rails-html-sanitizer-1.0.1
Installing ri documentation for rails-html-sanitizer-1.0.1
Parsing documentation for rails-deprecated_sanitizer-1.0.3
Installing ri documentation for rails-deprecated_sanitizer-1.0.3
Parsing documentation for rails-dom-testing-1.0.5
Installing ri documentation for rails-dom-testing-1.0.5
Parsing documentation for builder-3.2.2
Installing ri documentation for builder-3.2.2
Parsing documentation for erubis-2.7.0
Installing ri documentation for erubis-2.7.0
Parsing documentation for actionview-4.2.0
Installing ri documentation for actionview-4.2.0
Parsing documentation for actionpack-4.2.0
Installing ri documentation for actionpack-4.2.0
Parsing documentation for activemodel-4.2.0
Installing ri documentation for activemodel-4.2.0
Parsing documentation for arel-6.0.0
Installing ri documentation for arel-6.0.0
Parsing documentation for activerecord-4.2.0
Installing ri documentation for activerecord-4.2.0
Parsing documentation for globalid-0.3.0
Installing ri documentation for globalid-0.3.0
Parsing documentation for activejob-4.2.0
Installing ri documentation for activejob-4.2.0
Parsing documentation for mime-types-2.4.3
Installing ri documentation for mime-types-2.4.3
Parsing documentation for mail-2.6.3
Installing ri documentation for mail-2.6.3
Parsing documentation for actionmailer-4.2.0
Installing ri documentation for actionmailer-4.2.0
Parsing documentation for thor-0.19.1
Installing ri documentation for thor-0.19.1
Parsing documentation for railties-4.2.0
Installing ri documentation for railties-4.2.0
Parsing documentation for bundler-1.7.12
Installing ri documentation for bundler-1.7.12
Parsing documentation for hike-1.2.3
Installing ri documentation for hike-1.2.3
Parsing documentation for multi_json-1.10.1
Installing ri documentation for multi_json-1.10.1
Parsing documentation for tilt-1.4.1
Installing ri documentation for tilt-1.4.1
Parsing documentation for sprockets-2.12.3
Installing ri documentation for sprockets-2.12.3
Parsing documentation for sprockets-rails-2.2.2
Installing ri documentation for sprockets-rails-2.2.2
Parsing documentation for rails-4.2.0
unable to convert "\xFF" from ASCII-8BIT to UTF-8 for guides/assets/images/akshaysurve.jpg, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/belongs_to.png, skipping
unable to convert "\xF4" from ASCII-8BIT to UTF-8 for guides/assets/images/book_icon.gif, skipping
unable to convert "\x91" from ASCII-8BIT to UTF-8 for guides/assets/images/bullet.gif, skipping
unable to convert "\xF5" from ASCII-8BIT to UTF-8 for guides/assets/images/chapters_icon.gif, skipping
unable to convert "\xF5" from ASCII-8BIT to UTF-8 for guides/assets/images/check_bullet.gif, skipping
unable to convert "\xF4" from ASCII-8BIT to UTF-8 for guides/assets/images/credits_pic_blank.gif, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/csrf.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/edge_badge.png, skipping
unable to convert "\x9E" from ASCII-8BIT to UTF-8 for guides/assets/images/favicon.ico, skipping
unable to convert "\xF0" from ASCII-8BIT to UTF-8 for guides/assets/images/feature_tile.gif, skipping
unable to convert "\xF0" from ASCII-8BIT to UTF-8 for guides/assets/images/footer_tile.gif, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/fxn.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/article_with_comments.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/challenge.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/confirm_dialog.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/forbidden_attributes_for_new_article.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/form_with_errors.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/index_action_with_edit_link.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/new_article.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/rails_welcome.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/routing_error_no_controller.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/routing_error_no_route_matches.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/show_action_for_articles.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/template_is_missing_articles_new.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/unknown_action_create_for_articles.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/getting_started/unknown_action_new_for_articles.png, skipping
unable to convert "\xF0" from ASCII-8BIT to UTF-8 for guides/assets/images/grey_bullet.gif, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/habtm.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/has_many.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/has_many_through.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/has_one.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/has_one_through.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/header_backdrop.png, skipping
unable to convert "\xF0" from ASCII-8BIT to UTF-8 for guides/assets/images/header_tile.gif, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/i18n/demo_html_safe.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/i18n/demo_localized_pirate.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/i18n/demo_translated_en.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/i18n/demo_translated_pirate.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/i18n/demo_translation_missing.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/i18n/demo_untranslated.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/1.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/10.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/11.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/12.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/13.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/14.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/15.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/2.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/3.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/4.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/5.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/6.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/7.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/8.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/callouts/9.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/caution.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/example.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/home.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/important.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/next.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/note.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/prev.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/tip.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/up.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/icons/warning.png, skipping
unable to convert "\xF5" from ASCII-8BIT to UTF-8 for guides/assets/images/nav_arrow.gif, skipping
unable to convert "\xFF" from ASCII-8BIT to UTF-8 for guides/assets/images/oscardelben.jpg, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/polymorphic.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/radar.png, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/rails4_features.png, skipping
unable to convert "\xFF" from ASCII-8BIT to UTF-8 for guides/assets/images/rails_guides_kindle_cover.jpg, skipping
unable to convert "\xEC" from ASCII-8BIT to UTF-8 for guides/assets/images/rails_guides_logo.gif, skipping
unable to convert "\x8C" from ASCII-8BIT to UTF-8 for guides/assets/images/rails_logo_remix.gif, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/session_fixation.png, skipping
unable to convert "\x80" from ASCII-8BIT to UTF-8 for guides/assets/images/tab_grey.gif, skipping
unable to convert "\x80" from ASCII-8BIT to UTF-8 for guides/assets/images/tab_info.gif, skipping
unable to convert "\x80" from ASCII-8BIT to UTF-8 for guides/assets/images/tab_note.gif, skipping
unable to convert "\x80" from ASCII-8BIT to UTF-8 for guides/assets/images/tab_red.gif, skipping
unable to convert "\x80" from ASCII-8BIT to UTF-8 for guides/assets/images/tab_yellow.gif, skipping
unable to convert "\x89" from ASCII-8BIT to UTF-8 for guides/assets/images/tab_yellow.png, skipping
unable to convert "\xFF" from ASCII-8BIT to UTF-8 for guides/assets/images/vijaydev.jpg, skipping
Installing ri documentation for rails-4.2.0
34 gems installed
ontime:app-checklist rachelrolland$

### And Finally
- [ ] Create a pull request on GitHub from the branch of your name on your fork to the original Technology Checklist repository’s `master` branch; paste the pull-request URL here:
