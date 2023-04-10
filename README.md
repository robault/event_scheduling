# README

Thanks to the GoRails team for the great tutorial:

https://gorails.com/episodes/recurring-events?autoplay=1

---

This is a (working-ish) Rails 7 application showing the use of the recurring_select Ruby gem and the Javascript code from the recurring-select NPM package. Both have been modified to work with Rails 7 and hotwire/stimulus using importmap.

Kind of. 

Ideally the JS would be a component and added as an actual NPM package. But it needs more heavily modified for that to work. 

This is me, needing to move on to other things: ¯\\_(ツ)_/¯

---
Check out the gemfile for the additions. The updated Ruby gem is here:
https://github.com/robault/recurring_select

Uses Ruby 3.2.2

```bash
rbenv install 3.2.2
rbenv global 3.2.2
# exit and re-open terminal
```

Basic implementation taken from the GoRails tutorial but an event_controller.js has been added to handle the JS. (In: /app/javascript/controllers/event_controller.js)

The dialog is imported from the /app/javascript/controllers/lib directory. The jquery-mobile-rs.js.js is untouched but the index.js is my first attempt at turning it into a component. IT IS NOT GOOD CODE.  

And to be clear, it's not a 100% implementation of the GoRails tutorial. Just enough that you can see what's going on and how it works.

```bash
bundle install
bundle exec rake db:create db:migrate
bundle exec rails server
```

Bob's your uncle.

---

### Bit-o-fun

Check out Adrian Bliss's short videos on YouTube, he's hilarious!

https://www.youtube.com/@adrianbliss/featured

[![Adrian Bliss | In The Body Compilation](https://pbs.twimg.com/ext_tw_video_thumb/1543693544308834305/pu/img/-ZpJi5XOw2ExzHT6.jpg)](https://www.youtube.com/watch?v=6XzRCYfpjvE)
