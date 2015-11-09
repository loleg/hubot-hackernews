# hubot-hackernews

Shows the top stories from Ycombinator Hacker News

See [`src/hackernews.coffee`](src/hackernews.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-hackernews --save`

Then add **hubot-hackernews** to your `external-scripts.json`:

```json
[
  "hubot-hackernews"
]
```

## Sample Interaction

```
user1>> hubot hackernews
hubot>> Here are the latest news headlines:
[Writing the Prince symbol in Unicode (2013)](http://parkerhiggins.net/2013/01/writing-the-prince-symbol-in-unicode/)
[The Case for Melancholy](http://www.nytimes.com/2015/11/08/style/the-case-for-melancholy.html?smid=fb-nytimes&smtyp=cur)
[Another Crowdfunded Gadget Company Collapses](http://techcrunch.com/2015/11/07/another-1-million-crowdfunded-gadget-company-collapses/?ncid=rss&utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+Techcrunch+%28TechCrunch%29)
[Chronos Will Turn Any Watch into a Smartwatch](http://www.bloomberg.com/news/articles/2015-11-05/chronos-will-turn-any-watch-into-a-smartwatch)
[PostgreSQL Locking Revealed](http://blog.nordeus.com/dev-ops/postgresql-locking-revealed.htm)
```
