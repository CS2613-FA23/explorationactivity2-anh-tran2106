# Exploration Activity 2

Hello! I am Anh 👋

This repository is my work for the Exploration Activity #2 of CS2613 - Fall 2023 - University of New Brunswick.

## About this project

For this Exploration Activity, I will be looking into **Leaflet** - a JavaScript library for interactive maps. 

Specifically, I will be creating a website where you can view and explore the world map, as well as navigate to a Canadian City of your choice.

## Interative Map Demo 🗺️
![image](https://github.com/CS2613-FA23/explorationactivity2-anh-tran2106/assets/84007510/d6c51aa4-ddf5-410d-b6fd-b3a48b3faf29)


This demo's purpose is to demonstrates the use of the basic functionalities of [Leaflet](https://leafletjs.com/), allowing websites to display maps as well as interacting with them. It will also make use of [GeoDP Cities API](https://rapidapi.com/wirefreethought/api/geodb-cities) *(used in JavaScript PQ3)* to navigate the map to a selected Canadian City.

## Getting Started

### Prerequisites

Once you clone the project, open ```index.html``` in a code editor and change the ```apiKey``` to your own API Key at ```line 71``` .

The line should look like this:
```
const apiKey = 'a78dcab00dmsh943aa3f369bf5afp1ccfe2jsn781cf87a3fea';
```

If you've completed JavaScript PQ3. The API Key in your program should work here. Otherwise, make an Account on [RapidAPI](https://rapidapi.com/wirefreethought/api/geodb-cities) and get your API Key there.

After this, right clicking on the ```index.html``` file should take you to a browser where you can see the demo in action there.

## How to search

In order to search for a Canadian City, input the location in the field at the bottom of the screen in the following format:

```
City Name, Internationally Approved Alpha Code for Province/Territory
```

Press the **submit** button to perform the search.

You can see the full list of the internationally approved alpha codes [here](https://census.gc.ca/census-recensement/2021/ref/dict/tab/index-eng.cfm?ID=t1_8).

Some input examples:

```
Fredericton, NB
```

```
Moncton, NB
```

```
Toronto, ON
```
