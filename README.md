# Computer-Infrastructure

This is my project for the module Computer Infrastructure.

All work was completed on Github's [Codespaces](https://github.com/features/codespaces)

## Repository Structure
Within the repository there are 4 files and 1 directory containing 2 subdirectories.

- ### data
contains 2 sudirectories:

    - timestamps
        - 20241203_195608.txt an empty txt file with the name being the date and time of its inception.
        - formatted.txt contains a date and time in the format YYYYmmdd_HHMMSS.
        - now.txt contains 10 dates and times.

    - weather
        - contains 2 json files with weather data taken from the [Athenry weather station](https://prodapi.metweb.ie/observations/athenry/today)

- ### .gitignore
excludes typical files from Python projects.

- ### README.md
contains an overview of the repository.

- ### weather.ipynp
a jypter notebook containing information on how I performed Tasks 1 to 7.

- ### weather.sh 
a bash script to automate the fetching of the weather data from Athenry weather station and creating a json file with the current date and time that the file is being downloaded.
