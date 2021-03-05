# StoryMap Proof-of-Concept
Knightlab's [StoryMap JS](https://storymap.knightlab.com/) is a fantastic visual editor for interactive maps. One shortcoming, though, is that it doesn't allow for collaborative editing of the map. That's kind of a dealbreaker if you want to use it for team projects in the classroom.

This is a proof-of-concept for collaborative creation of StoryMaps, hosted by Github Pages. Because the StoryMap Javascript module populates its maps with data from a JSON file, you don't *need* to use the official Knightlab site. All you need is a JSON file and a [few lines of code](https://storymap.knightlab.com/advanced/) in an index.html file. Put both in a Github repo and publish to Github pages. Then, teams can collaboratively edit the JSON file using any JSON editor. Each group can push changes to the JSON file to the repo. As soon as they're accepted into the Master branch, they appear on the published StoryMap page.

You can also host the JSON in a Github Gist, which might make it easer for team members to edit. Because JSON is very fussy, you should probably use [JSONLint](https://jsonlint.com/) or [JSON Blob](https://jsonblob.com/1360ce72-7dc6-11eb-b747-2bcd29c52918) to verify the validity of the formatting.

* [Demo StoryMap](https://samplereality.github.io/storymap/)
* [Demo JSON](https://gist.github.com/samplereality/4b24d467450631c59c65b72659408b14) in a Gist
