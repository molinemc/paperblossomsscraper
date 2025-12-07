# paperblossomsscraper
Creates a user descriptions file for import into Paper Blossoms from L5R sourcebooks

You will need to drop PDFs of L5R sourcebooks in the local folder where you download this, 
as well as the PaperBlossoms json files located [here https://github.com/Cvelth/PaperBlossoms/tree/master/PaperBlossoms/data/json].
Then, run the following commands:
	python3 -m venv .venv
	python -m pip install -r requirements.txt
	python -m scrape
	
This should create a new user_descriptions.csv file containing descriptions from your local sourcebooks.
Note that this software is not well-tested, will produce some funny-looking lines, and may not be ready for
your sourcebook. It's been tested with the Core Rulebook, the Mantis clan DLC, Courts of Stone, and Path 
of Waves.

This software as-is, I make no promises. Good luck.