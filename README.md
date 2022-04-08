# Outreachy-Wikidata-project.
This is the python code for task 2 under the project: What's in a name? Automatically identifying first and last author names for Wikicite and Wikidata.

# DESCRIPTION OF TASK.
This is the second task for T300207, What's in a name? Automatically identifying first and last author names for Wikicite and Wikidata, aimed at getting you familiar with Pywikibot.

You should register a Wikimedia account if you don't already have one. You can do so at https://www.wikidata.org/w/index.php?title=Special:CreateAccount
You should download and install Python 3 and pywikibot - see instructions at https://www.mediawiki.org/wiki/Manual:Pywikibot/Installation . You will need to set up a user configuration file, and make sure you can log in. Set 'wikipedia' as the base family, and then manually add usernames['wikidata']['wikidata'] = u'Your username' into the generated user-config.py file. If you want, you can set a bot password (see https://www.mediawiki.org/wiki/Manual:Pywikibot/BotPasswords ) and use that - or use your normal Wikimedia login information.
Set up a script that will connect to Wikidata, load the 'Outreachy_1' page that you created in the previous task, and print it out.
Try adding 'Hello' to the end of the page you just loaded, and save it back.
Load a Wikidata item (use 'Q4115189' to start with - it is the sandbox), and print out information from it. You can then try loading the items for the scientific articles you looked at in the first task. You should try to print out all of the author information that is available in the item (at least the names, ideally also the qualifiers).
Bonus: automatically follow links to items about the authors, and print out their name information as well (e.g., given/family names).

Save your code to a repository, or create a page like https://www.wikidata.org/wiki/User:Mike_Peel/Outreachy_2 (under your username)

Once you are happy, send me a link to your page (by email, on my talk page, or replying to this ticket as you prefer). Make sure to also register it as a contribution on the Outreachy website ( https://www.outreachy.org/outreachy-may-2022-internship-round/communities/wikimedia/whats-in-a-name-automatically-identifying-first-an/contributions/ )!

Hints:

You can find examples in https://github.com/mpeel/wikicode/blob/master/example.py
And more at https://www.mediawiki.org/wiki/Manual:Pywikibot/Create_your_own_script
And https://www.mediawiki.org/wiki/Manual:Pywikibot/Wikidata
