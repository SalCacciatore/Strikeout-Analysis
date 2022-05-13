# Strikeout-Analysis 

This project will analyze the importance of strikeouts in Major League Baseball. Strikeouts have reached historic levels in recent years and the project will consider the impact of this and examine why scoring has not declined in tandem with this increase.

One of the key takeaways here is that strikeouts are crucial for pitching success but not necessarily a detriment to offensive success on their own.

The analysis covers over a century of baseball history, and utilizes data from <a href="https://www.retrosheet.org">Retrosheet.</a> It also utilizes data from Baseball-Reference.com and FanGraphs.com (the latter via <a href="https://github.com/jldbc/pybaseball">PyBaseball).</a>

It has three main components:
<ul>
  <li>An examination of the rise in strikeout rate</li>
  <li>How this rise has effected scoring</li>
  <li>Why these effects are different for run scoring and run prevention</li>
</ul>

The project uses the 'Strikeout_analysis.ipynb' Jupyter Notebook and the following datasets:
<ul>
  <li>pitchers_16_21.csv -- this is a csv file with Baseball Reference data for individual pitchers from 2016 to 2021</li>
  <li>Game logs from Retrosheet, which can be downloaded here: https://www.retrosheet.org/gamelogs/index.html</li>
</ul>
