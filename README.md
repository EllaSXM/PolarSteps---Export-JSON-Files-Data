# Extracting Your Data From PolarStep's JSON Files

Hello Fellow Travelers! 

**Why did I write this code?**
During my yearlong travel sabbatical I used Polar Steps as a journal to document my daily thoughts, photos and location. After coming back, I wanted to save my journal entries and location data safely so that I still have that information in 10, 20, 30 years time. Very few apps surivve that long. So I requested my data from PolarSteps. They sent me JSON files (sigh) with MANY nested lists (sigh again) and so I wrote this code to extract my journal entries into a more useable format. 

**What does the code do?**
The code outputs the following files
- 1x Wordfile with all entries in one place.
- Wordiles of journal entries saved by month. I travelled for a year so I had 12 files. This is redundant but - why not?
- A text file for every journal entry by date. Because text files are more future proof than wordfiles. 

Information in each file
- Date
- Jounal Title
- City/Place Location
- Country Location
- Journal Entry

Notes
In short, the codes extracts the date of each entry, location, journal title and text. You'll see that the dataframe (table) in Python contains extra information that I extract like weather and temperature. I wanted to keep the journal extracts simple so left them out. You could rejig the code to include them.  

**Why am I sharing this, when you could have a chance to rant and be upset with PolarSteps and the World?**
Well, I looked online and couldn't find any reports of anyone who had done this using Python. There was one person who had done extracted their data from Polar Steps with R and poster their code. So, I saw this as a challenge to work on my python coding skills and upload a first GitHub post. See, once I stopped travelling, I felt a bit lost and needed a new hobby. And honestly, it would be great if other people saved time and could access their own data with my code. Cheers!

**OK Some Helpful Notes to Actually Use The Code.**

1. You need to request your data from PolarSteps. This can be done somewhere in settings in the app. I'm sure you'll find it. Polar Steps provides a guide to this on their website. 
2. Once you get the data, look for the JSON files. I found them at the bottom of the files. The files I used are "locations.json" and "trip.json".
3. Load the files in python and run the code.
4. Hope it works and that you don't need to tweak it.
5. Go through your extracted files in 10 years and cherish those memories!
   
