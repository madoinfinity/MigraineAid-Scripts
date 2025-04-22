# MigraineAid-Scripts

MigraineAid is an Android Java application made for people who suffer from migraines. The project is in the intersection of both Software Engineering and AI. We collect two different forms of data: sensor and user-logged data to enable a feature-rich dataset. The first one uses mobile device sensors and we gather data such as location, step count, gyroscope data, brightness, screen time data. The latter is in the form of daily logs which the users are expected to log daily for a consistent stream of data making it suitable for machine leanring. We recognize that this is a time series problem and we have developed a framework which starts with employing individual LSTMs for each user and then clustering based on similarities across users to develop refined models which can apply to multiple patients.

This directory contains a few samples of code in which data is anonymized but still shows our research and analysis. 
