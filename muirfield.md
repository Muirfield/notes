# Muirfield


## WP mf-forms

- Post approval workflow (automatic publish topics, trash topics)
  - https://codex.wordpress.org/Plugin_API/Hooks_2.0.x
  - https://wordpress.org/support/topic/add_action-with-publish_post:
    - add_filter('publish_post','function');
  -  If you want to confirm that your hook is working, use update_option(), and delete the option immediately after displaying it so it's not latent (alternatively: you can make the option count up or something, there's quite a bit you could do, be creative).

* * *

- Templates from posts/pages
- Allow post with tabbed page
- Switch to a different github api library (lighter)

## Eval

- automatic-post-tagger

* * *

## Tech features

- basic core
   - raklib
   - spl
   - network
   - nbt
   - level/world
   - command dispatcher
- multi threaded

* * *

WordPress

  - blog : announcements and articles
  - product catalogue plugin
     - plugins and servers?
     - categories
     - reviews
     - related links
     - forum links
  - forum plugin bbPress
  - BuddyPress plugin for Social aspects (no forum)
  - live chat plugin (with log)
  - github login integration
  - hosted on openShift

ticket/issue tracker: github

- https://meta.trac.wordpress.org/browser/sites/trunk/wordpress.org/public_html/wp-content/plugins/plugin-directory
- https://wordpress.org/support/topic/front-end-custom-form-to-post
- https://blog.madewithlove.be/post/thread-carefully/
- http://www.programering.com/a/MjN5YDMwATU.html
- http://forums.devshed.com/php-development-5/multithreading-php-948403.html
- https://github.com/krakjoe/pthreads/tree/master/examples
-  https://wordpress.org/plugins/wp-imgur/
- https://wordpress.org/plugins/badgeos/
- https://wordpress.org/plugins/badgeos-community-add-on/

Develop:

Create own forms: https://www.sitepoint.com/build-your-own-wordpress-contact-form-plugin-in-5-minutes/

- https://wordpress.org/plugins/pcsh-pastacode-syntaxhighlighter/
- https://wordpress.org/plugins/enlighter/
- https://wordpress.org/plugins/crayon-syntax-highlighter/


# GitHub Integration

## Login

- https://wordpress.org/plugins/mm-github-connect/
- https://wordpress.org/plugins/wordpress-social-login/

* * *


1. create post
2. Pick categories 
