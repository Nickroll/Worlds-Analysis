# Worlds-Analysis
This is some basic analysis and graph making done on the worlds data provided by the wonderful people over at http://oracleselixir.com/

All of the graphs images and code can be used by anyone this was done for fun and practice on data analysis. Just make sure to credit me or link to the github you got the graphs from.

::: EDIT :::

A new fillable form has been added. Under the Role Analysis folder there is a Role Analysis (Fillable).ipynb. This notebook will create a graph for you based on the average performance of which ever role you want during worlds group stage. 

:: Instructions :: 
1) Download the Data dir and the Role Analysis dir. 
2) In cell 3 replace Role in to your desired role 
  Ex: Role_mask = player_data['position'] == 'Role' ::TO:: Role_mask = player_data['position'] == 'Top'
3) Change strings in cell 6 from 'Average Role ...' to 'Average Top ..'
4) Uncomment the final line

:: Optional ::
You can also change what is being looked at by changing the 'gdat10' and 'gdat15' in the following lines:

temp_sort = Role_stats_avg.sort_values(by = 'gdat15')
gdat10 = list(temp_sort['gdat10'].values)
gdat15 = list(temp_sort['gdat15'].values)

To whatever value you want to comapre. The list of comparable options is found at: http://oracleselixir.com/match-data/match-data-dictionary/

::: EDIT :::

The final images and grpahs are found in the individual Final directories which also include the ipynb files that I used to make the graphs. 

I'll be updating this periodically with new graphs.

If you wnat to contact me my email is rick.nickroller@gmail.com
