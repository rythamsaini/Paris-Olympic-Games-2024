
# Paris 2024 Olympic Summer Games Dataset

# Overview

This dataset provides comprehensive information related to the Paris 2024 Olympic Summer Games. It includes details on events, athletes, countries, medals, venues, and more. The data is structured to facilitate analysis and information visualization, offering insights into the various aspects of the Olympic Games.

# Dataset Contents

The dataset is composed of several CSV files, each representing different facets of the Paris 2024 Olympic Summer Games. Below is a description of each file:

# 1. `events.csv`
- Description: Contains a list of all events in the Paris 2024 Olympic Games, including details such as event names, categories, and associated sports.
- Columns:
  - `event_id`: Unique identifier for the event.
  - `event_name`: Name of the event (e.g., Men's 100m).
  - `sport`: The sport to which the event belongs (e.g., Athletics).
  - `category`: The category or discipline within the sport (e.g., Track, Field).

# 2. `athletes.csv`
- Description: Contains detailed information about the athletes participating in the Games.
- Columns:
  - `athlete_id`: Unique identifier for the athlete.
  - `name`: Full name of the athlete.
  - `gender`: Gender of the athlete (Male/Female).
  - `country_code`: ISO 3166-1 alpha-3 code of the athlete's country.
  - `dob`: Date of birth of the athlete.
  - `sport`: The sport in which the athlete is competing.

# 3. `countries.csv`
- Description: Provides information about the countries participating in the Paris 2024 Olympic Games.
- Columns:
  - `country_code`: ISO 3166-1 alpha-3 code of the country.
  - `country_name`: Name of the country.
  - `continent`: The continent to which the country belongs.
  - `nocs`: National Olympic Committees (NOCs) of the country.

# 4. `medals.csv`
- Description: Contains data on the medals awarded during the Games, including the events, athletes, and countries that won them.
- Columns:
  - `medal_id`: Unique identifier for the medal record.
  - `event_id`: Identifier of the event in which the medal was awarded.
  - `athlete_id`: Identifier of the athlete who won the medal.
  - `country_code`: Country code of the athlete's country.
  - `medal_type`: Type of medal (Gold, Silver, Bronze).

# 5. `venues.csv`
- Description: Lists the venues where the events are held, including information about their location and capacity.
- Columns:
  - `venue_id`: Unique identifier for the venue.
  - `venue_name`: Name of the venue.
  - `location`: Location of the venue (e.g., Paris, France).
  - `capacity`: Seating capacity of the venue.

# 6. `schedules.csv`
- Description: Provides the schedule for all events, including dates, times, and venues.
- Columns:
  - `schedule_id`: Unique identifier for the schedule entry.
  - `event_id`: Identifier of the event.
  - `date`: Date of the event.
  - `time`: Time of the event.
  - `venue_id`: Identifier of the venue where the event is held.

# Usage

This dataset is ideal for information visualization projects related to the Olympic Games. Some possible visualization ideas include:
- Medal Distribution: Visualizing the distribution of medals across countries and sports.
- Event Participation: Analyzing the participation of athletes in different events.
- Venue Utilization: Mapping the usage and capacity of different venues.
- Gender Representation: Exploring gender distribution across sports and countries.

# License

This dataset is provided under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). You are free to use, modify, and share the data, provided that appropriate credit is given.

# Acknowledgments

This dataset has been compiled using publicly available data related to the Paris 2024 Olympic Summer Games. We would like to acknowledge the efforts of the organizers and contributors who made this data accessible for research and educational purposes.
