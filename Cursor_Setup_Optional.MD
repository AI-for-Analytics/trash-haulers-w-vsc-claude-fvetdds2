## Setting up Cursor

- Go to www.cursor.com and download.
- Install (You may want to select option for desktop icon)
- Sign up
- Open Cursor (No need to change any options for this demonstration)
- Open Project - Select the trash haulers repo
- Start with a simple request like
  "Use the trash_hauler_with_lat_lng.csv to tell me which trash hauler occurs most frequently"
- Cursor is able to this and more complex tasks.  In this trial version you will be limited to amount of work you are able to have Cursor do.
  Explore.  Instruct Cursor to answer some of the questions in the README (Or invent your own) and see how it handles it.  
- On other projects I could see Cursor being helpful handling time-intensive tasks while allowing you to focus on the analysis as a whole.
- The questions below are more complex.  You can use these too to see how Cursor will handle it.

### Alternative Method 1:

For each address, if there are three or more missed pickups within a 180-day period, damages of $1500 will be charged. (A fine will be levied every time three unique missed pickup dates occur within a six-month period for a single address.)


### Alternative Method 2:

This method also considers the six-month window like Alternative Method 1, but each date can only be used once to support a fine. How will this difference impact the fines levied? (Example: If Jan 1st, Mar 3rd, Apr 8th, and Aug 9th were the only four dates a trash pickup was missed, the original method would result in $3000 in fines [Jan, Mar, Apr, and also Mar, Apr, Aug]. However, this updated method would only result in $1500 because neither Mar nor Apr can be used for another fine since they were already used.)
