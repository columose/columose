# Colum Ó Sé

**`Data science`**

Welcome to my Github profile ![wave-gif](https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/gifs/wave.gif)

I was introduced to data science through my work in biosignal processing of EEG data at academic institutions. Aside from academia, I have pursued data science projects to improve my programming skills, to work with real world data (Spotify API,  World Organisation for Animal Health, NOAA Earthquake data) and to explore nice methods for data storage on cloud servers.

I use Github to showcase some of my projects, collaborate with others, and share code with other data scientists.

### 🧰 Programming and querying tools

<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="MATLAB" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" />
<img align="left" alt="sqlite" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" />
<br />

#

### Data analytics portfolio
Through my background in data science and cognitive neuroscience, I have gained strong skills in programming (Python, MATLAB), web scraping, database storage (MySQL, BigQuery) and querying (SQL), statistics, data analytics, data visualisation, and oral presentation.

In this portfolio, I showcase my data science skills through 4 separate projects. My description of the projects are brief as code and figures can be found in their corresponding repositories.

### *Project 1: Cloud-based web-scraping project using Spotify API*
* ***Entirey cloud-based project*** scraping ***real-time data*** from Spotify API using ***Python*** scripts.
* Data was scraped and cleaned from Spotify API using the Pandas module with ***Google Colab*** for efficient ***cloud-computing***.
* Clean daily data from the 'Top-50 Ireland' playlist, and clean annual data from 21st century playlists, is stored in ***Google Big Query*** data warehouse.
* The key metrics of daily Irish top charts are compared with annual trends from the 21st century using an [interactive dashboard](https://lookerstudio.google.com/reporting/89c6378a-f65c-40d0-b712-72041bbcd563) in ***Google Looker Studio***.
* A detailed description of the project, code, and interpretation of results can be found at the following [repository](https://github.com/columose/Spotify-API/blob/d85f87640ab00f4edf8d388ffddec082292d8064/README.md).

![Dashboard](https://github.com/columose/Spotify-API/blob/c4cdf184cf44efd278bfab140fcb2f333473ca25/Images/Spotify%20API%20dashboard.png)

#### *Project 2: World Organisation of Animal Health dataset*
* Extracted real-world data relating to *Foot and Mouth disease (FMD)* in animals from the *World Organisation of Animal Health's* public database.
* Data was cleaned (removing duplicate entries, Nan values, etc.) using the Pandas module with ***Google Colab*** for efficient ***cloud-computing***
* Stored clean dataset on ***MySQL*** server.
* Performed time-series analysis to determine when peaks in variables of interest occurred and further explored whether variables of interest appeared to be related (NumPy, Matplotlib, Seaborn).
* Deployed ***regression models*** to determine that FMD outbreaks in Europe have been dealt with by increased culling rates (scikit-learn).
* Summarised key metrics using an [interactive dashboard](https://public.tableau.com/app/profile/colum.s./viz/WOAHFMDproject/Dashboard) in ***Tableau public***.
* Detailed description, code, figures, and interpretation can be found at the following [repository](https://github.com/columose/WOAH-FMD-dataset.git).

![figure](https://github.com/columose/WOAH-FMD-dataset/blob/5765e91a983e9fdf36988e3aa3fee5f0fae095d9/Figure%20output/Dashboard.png)


#### *Project 3: Auditory oddball experiment*
* Cleaned dataset by following a standard EEG preprocessing protocol - removal of artifacts (ECG, eyeblinks), bandpass filtering to remove line noise, removing noisy trials and channels, removing independent components that were non-signal related, interpolating any removed bad channels.
* Performed time-series and time-frequency analyses of event-related signals.
* Visualised the results of intricate statistical analyses using ***MATLAB and Python (Matplotlib, Seaborn, MNE)***.
* The results of this project indicate that pre-attentive neural responses to environmental irregularities become heightned in chronic pain patients to compensate for attentional deficits.
* Detailed description, code and figures can be found at the following [repository](https://github.com/columose/Chronic-Pain-Project.git).

![figure](https://github.com/columose/columose/blob/8ad6cd6b904a5fcb0a8c0192ecebb4ee1c83f5e4/Github%20figures/Oddball%20time-domain.png)

![figure](https://github.com/columose/columose/blob/aa0001208ff6838ab751deaa0b7fb6cf3548dee2/Github%20figures/Oddball%20time-freq.png)

#### *Project 4: Colour surface perception*
* Cleaned dataset using standard EEG protocol (see project 3).
* Performed spectral analyses of frequency-tagged ERPs and visualised the results of statistical tests using ***MATLAB***.
* Presented findings of research study at a national conference.
* The figures below capture the findings of our study quite nicely. Illusory 'filling-in' of surfaces occurs with a 'spreading-out' of cortical activity. 
* For access to the complete thesis and poster, see the following [repository](https://github.com/columose/Colour-Perception.git). 

![figure](https://github.com/columose/columose/blob/bd11dc061999938ed605dfc0232e398c65ec407b/Github%20figures/Colour%20perception.png)
















