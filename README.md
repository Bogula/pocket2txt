# pocket2txt

After July 8, Pocket will move into export-only mode. 
Users can export saves anytime until October 8, 2025, 
after which user data will be permanently deleted.

https://support.mozilla.org/en-US/kb/future-of-pocket#:~:text=Need%20help%3F-,When%20is%20Pocket%20shutting%20down%3F,available%20after%20July%208%2C%202025.

Using the export function of pocket results in a csv with:
Title (sometimes just the URL), the url to the pocketed website, timestamp, tags and status

I thought it might be useful to extract the content of all my 3500 pocketed websites,
I never found the time to read it, for clustering, sorting out the useful stuff and
use it as database for a RAG-based chatbot.

Here is the script that takes the exported .csv from Pocket and
results in a list of cleaned up text contents of the websites. 

Just vibe-coded not optimzed , just fire and forget

