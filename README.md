# README

Thanks to the GoRails team for the great tutorial:

https://gorails.com/episodes/recurring-events?autoplay=1

---

This is a (working) Rails 7 application showing the use of the recurring_select Ruby gem and the Javascript code from the recurring-select NPM package. Both have been modified to work with Rails 7 and hotwire/stimulus using importmap.

Kind of. 

Ideally the JS would be a component and added as an actual NPM package. But it needs more heavily modified for that to work. I'll continue to work on it because so far it has been fun. But I'm also not a super strong JS dev so it may take a bit to finish. Send me a message if you're interested so I know someone else actually cares. 

This is me, working in a vacuum: ¯\_(ツ)_/¯

---

The updated Ruby gem is here:
https://github.com/robault/recurring_select

Uses Ruby 3.2.2

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

{% include youtube.html id="6XzRCYfpjvE" %}