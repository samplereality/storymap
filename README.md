# StoryMap Proof-of-Concept
Knightlab's [StoryMap JS](https://storymap.knightlab.com/) is a fantastic visual editor for interactive maps. One shortcoming, though, is that it doesn't allow for collaborative editing of the map. That's kind of a dealbreaker if you want to use it for team projects in the classroom.

This is a proof-of-concept for collaborative creation of StoryMaps, hosted by Github Pages. Because the StoryMap Javascript module populates its maps with data from a JSON file, you don't *need* to use the official Knightlab site. All you need is a JSON file and a [few lines of code](https://storymap.knightlab.com/advanced/) in an index.html file. Put both in a Github repo and publish to Github pages. Then, teams can collaboratively edit the JSON file using any JSON editor. Each group can push changes to the JSON file to the repo. As soon as they're accepted into the Master branch, they appear on the published StoryMap page. 

* [Demo](https://samplereality.github.io/storymap/)
* Underlying JSON
