# dataTableTop
A board game logger GUI
Visit https://dpreid.github.io/strategic-thought/coding_datatabletop.html to find out more about DataTableTop including some screen shots
of the main features.

Install: DataTableTop is an executable JAR file, so all you need is the Java Runtime Environment in order to run it. Once you have downloaded
the package, simply place the executable file and associated folder in a suitable location. Three files will be generated with use of the program:
game_data and player_data bin files and a CSV of all the individual games logged. These will all be generated in the same location as you place
the executable file.

The program is fairly simple and self-explanatory: creating players and games is done in the menu files in the top bar. The Data menu gives you access
to the 3 ranking systems (overall points, average points and win percentage) as well as a simple graph of points over time.

Players and games can be deleted, but if those games have been played by players then these remain tracked in their total games played.
If data is entered incorrectly then the latest data can be deleted. However, specific data entries cannot be selected for deletion, you would have
to work back deleting all games to that point, then rentering data from a backup of the CSV file.

BACKUP: Since deleting games can be an issue if a lot of data has been entered since then, I recommend making a backup of the CSV file regularly.
When deleting the last data entry, the last line in the CSV file is also deleted, so if you want to re-enter those games you will need a copy of the 
CSV file to remain unchanged.
