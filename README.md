infinitydevice
==============

A never ending science fiction story, with different paths and outcomes as time ebbs and flows. 

Twitter: [nfntydvc](http://twitter.com/nfntydvc "nfntydvc")


Brief
-----

A story is data, it can be read as a series of sequential characters, groups of paragraph strings in an array, or perhaps something more complex. As the story progresses there will be many branches, and events that can cascade through myltiple storylines.


I am curious to see how such a freeform of storytelling can be indexed and accessed. The most basic being to surface a certain story based on the readers responses. Even more interesting would be to have the story 'generate' based on the season, the location from which accessed, even currently trending news reports on the internet.

Check out the Phase II samples to get an idea of what the project aims to achieve.

Phase I
-------

Mashup stories from internet sources, creating entirely novel and often unintelligible results for the inspiration of new stories.

Usage
-----

* Download `masher.rb` or clone the repo.
* The `nokogiri` and `redcarpet` gems are required to run the code in it's current state.
* Open up `masher.rb` in your text editor, check out the comments and change parameters as you like.
* Run the script with `ruby masher.rb`. This might take awhile depending on your options and Fanfiction.net servers.
* Your story will be saved to `story.md` (Markdown format) and `story.html` (HTML format).
* Enjoy :)

* A `cache.yaml` file which contains all the data scraped will be saved once you've run the script. If you want to reuse these results with new parameters you can set `FETCH_LIVE_DATA = false` in the script.

Phase II (in progress)
--------

Parse wikipedia history timelines and wikia fictional history timelines to create branching non-fiction/fiction time pathways to develop timeline frameworks for new alternate realities.

Phase III (in progress)
---------

Adding to the history database, add new timeline entries using twitter.

Scans for tweets with the (time)(day)(month)(year)(text)(#story) format, where a tweet will be saved if it contains >=3 of the required parameters. Anyone can write or contribute to a book simply by tweeting out their ideas.

Serve up timelines based on criteria above and other operators that effectively group stories.

Allow users to edit and save generated timelines, as well as including full stories in-line.


Phase IV (future)
---------

Songza-style generator. Serve up stories to the user from saved timelines with a few clicks of mood criteria, current events, and trending topics. 


