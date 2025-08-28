--What locations have the highest propensity to experience forest fires
select top 10 * from Forestfires where FFMC > 80
order by FFMC DESC

--what locations actually experienced forestfires
select * from Forestfires where area > 0
order by area Desc

--what season is forest fires most likely to occur
select Season, sum (area) as Total_area, sum(FFMC) as Total_FFMC from Forestfires
group by Season
order by Total_area DESC

--what month has the largest burnt area by forest fires
select month, sum (area) as Total_area from Forestfires
group by month
order by Total_area DESC

