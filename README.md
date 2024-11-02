Merge Population and Obesity Data

You are given two datasets: sample1 containing obesity rates by country and sample2 containing population figures by country. Each dataset has three columns: "Pos", "Name", and "Value." The "Pos" column represents the rank of the country, "Name" is the country name, and "Value" contains the respective population or obesity rate.

Your task is to merge these two datasets on the "Country" column and extract the "Country," "Population," and "Obesity Rate" columns. After merging, filter the resulting dataset to include only countries with an obesity rate greater than 20 and a population greater than 10,000,000. Finally, sort the filtered dataset by obesity rate in descending order and return the top 10 countries.

