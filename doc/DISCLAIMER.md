### Feed Configuration

Feed configuration is handled by a plaintext file on the host system. By default this configuration would be located in a `feeds.txt` file within the path `/home/yunohost.app/rss`.

The format of this file can be seen below:

```
https://feed.url.com/feed.xml feed-name #tag-a #tag-b
https://example.com/feed.xml Example #updates #news

# Lines starting with a hash are considered comments.
# Empty lines are fine and will be ignored.

# Underscores in names will be converted to spaces.
https://example.com/feed-b.xml News_Site #news

# Feed color can be set using square brackets after the name.
# The color must be a CSS-compatible color value.
https://example.com/feed-c.xml Blue_News[#0078b9] #news #blue
```
