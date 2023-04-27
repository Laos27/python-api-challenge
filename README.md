# python-api-challenge

The codes for this task are located in the repo Laos27/python-api-challenge, inside the folder WeatherPy/starter_code.
Some Files were generated after running the code and these are located inside the folder WeatherPy/output_data.

Please take into account this code was run with the kernel: base(Python 3.9.16). I tried to run with Python Data and did not work for me. I followed all the steps shared by the Instructors in Slack but still not succesful. That's why I used the kernel mentioned above.

I had some challenges when creating the cities weather data into a Pandas Dataframe as there were some cities that were not found in the Weather API and the lenght of the array with the rest of results did not match. 
I used some references codes that advised to create a list with all the removed cities and then remove these ones from the original Cities list. Once these ones were removed, I could create the Pandas Dataframe as all the columns had now the same lenght.

Both codes run without problem. And all the maps were also generated without issues for the 2nd part of this challenge.