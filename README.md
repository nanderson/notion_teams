# notion_teams
Report on team details with Notion.so as a back-end



Inspired by a work discussion regarding team structures. I wanted to create a simple way to store info on our Engineering teams (names, people, roles, etc) so I could deliver that information via the web, Slack bot, etc. We already use Notion.so as our engineering wiki so this made the most sense.


# To Do
* revise documentation
  * notion page & collection
  * installation
    * > python3 -m pip install notion
    * notion page & collection details
    * config file fields
* clean up code massively (it's still very much in a POC phase)
* make a notion template for the team listing & share it
* separate functions for:
  * full team listing (subset of full info?)
  * single team, full details (don't randomize dev list)
  * single team stand-up order (randomize dev list)
* Slack bot
  * AWS Lambda and/or DO Dropplet, something simple
* look into newer Notion.so REST API and/or newer SDKs & clients
  * coookie thing is ugly, need something better
* don't really need anything from the parent page, could get rid of that extra details
* describe other ways to use & format the collection within Notion.so
* JSON sucks for config files (lack of comments), move to YAML?
