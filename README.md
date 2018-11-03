### Simplerss
---
https://github.com/cardmagic/simple-rss

```ruby
require 'rubygems'
require 'simple-rss'
require 'open-uri'

rss = SimpleRSS.parse open('http://slashdot.org/index.rdf')

rss.channel.title
rss.channel.link
rss.items.first.link

rss.feed.title
rss.feed.link
rss.entries.first.link

SimpleRSS.feed_tags << :some_new_tag
SimpleRSS.item_tags << :"item+myrel"
SimpleRSS.item_tags << :"feedburner:origLink"
SimpleRSS.item_tags << :"media:content#url"

```

```
```

```
```


