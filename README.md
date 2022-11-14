# HLTB-unipd
Group Project for Database 2 at University of Padua 

## Topic
The main modelled topic are video games and their completion time from www.howlongtobeat.com. To this we added sales data from www.vgchartz.com.

### Execution Order

1. **HLTB_scraper.ipynb**, to retrieve additional completion time for games.Takes several minutes to execute.
2. **Platforms.ipynb**, to clean platforms datasets.
3. **indiegamesdevelopers&games&vgchartz&videogamesdevelopers_cleaning.ipynb**, to clean datasets.
4. **HLTB_RDF_Creatory.ipynb**, to generate .ttl files. Takes several minutes to execute.


### Source Datasets
All source datasets are in the *raw_datasets* folder


- *games.csv* &rarr; game data and completion time from www.howlongtobeat.com. Retrieved from https://www.kaggle.com/datasets/kasumil5x/howlongtobeat-games-completion-times
- *indie-game-developers.csv* and *video-games-developers.csv* &rarr; developer names with the headquarters country and notable games. Retrieved
  from https://www.kaggle.com/datasets/andreshg/videogamescompaniesregions
- *vgchartz-7_7_2020.csv* &rarr; sales data for videogames present on the vgchartz website. Retrieved from https://www.kaggle.com/datasets/baynebrannen/video-game-sales-2020
- *plaforms/console_sales_vgchartz.csv* &rarr; sales data for console platforms. Retreived from the web page  https://www.vgchartz.com/charts/platform_totals/Hardware.php/
- *plaforms/platforms_hltb.txt* and *platforms/popular_platforms_hltb.txt* &rarr; list of console platforms available on the howlongtobeat website. Retrieved from https://howlongtobeat.com/stats 
- *platforms/platforms_wikipedia.csv* table with console platforms information. Retrieved from https://en.wikipedia.org/wiki/Home_video_game_console#Released_systems