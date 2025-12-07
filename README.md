# paperblossomsscraper
Creates a user descriptions file for import into Paper Blossoms from L5R sourcebooks

Steps to make work.
1. Drop PDFs of L5R sourcebooks in the local folder where you clone this repository, 
as well as the PaperBlossoms json files located [here](https://github.com/Cvelth/PaperBlossoms/tree/master/PaperBlossoms/data/json).
2. Ensure python is installed. On some versions of linux, you may need to install python-venv as 
a separate package.
3. Open your command line.
4. Navigate to the repository folder.
5. Execute the following:
```
	python3 -m venv .venv
	python -m pip install -r requirements.txt
	python -m scrape
```
	
This should create a new user_descriptions.csv file containing descriptions from your local sourcebooks.
Note that this software is not well-tested, will produce some funny-looking lines, and may not be ready for
your sourcebook. It's been tested with the Core Rulebook, the Mantis clan DLC, Courts of Stone, and Path 
of Waves.

This software as-is, I make no promises. Good luck.