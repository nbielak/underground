# Underground

Underground is an interactive app that allows users to explore new releases by local artists, using bandcamp as a datasource. Users may input a specific city in the search bar, at which point, circles of a size relative to the popularity of a genre will fill the screen.  Clicking on a circle will create list of the most recent uploads to that genre, with tabs at the top to select specific sub-genres.  Each list item will display the artist's information and link to that artist's page on bandcamp.

## MVP

- [ ] Pulls correct information from bandcamp's website
- [ ] Represents genres as circles with correct sizing
- [ ] Users can specify subgenre
- [ ] Hovering over a circle gives a pie chart of subgenres
- [ ] List items link to artist's page

## WireFrames

Underground will consist of a search bar at the top, prompting users to search by city, and links to my github and linkedin.  

Underneath, there will be a display for the the genres on the left, and on the right, the list of bands and sub genres to the left.  Each of the genre bubbles will include a description of the genre as well as statistics concerning that genre.

![underground](https://user-images.githubusercontent.com/40076454/44319843-3c5e6600-a3f3-11e8-9d30-b3be6a40c8eb.jpg)

## Technology

`scraper.js` will get and be the main source of data.

`graph.js` will handle rendering the data on the graph as circles.

`genre_links_list.js` will break down each genre by subgenre and provide a list of links to artist pages.


I will use `JQuery`, `node.js`, `Cheerio`, and `Request` to scrape bandcamp and `webpack` to bundle all the scripts.

## Implementation Timeline

### Over the weekend

* Familiarized myself with the bandcamp API

* watched tutorials on `cheerio`, `request`, and website scraping

### Day 1

* Set up scraper to pull information off of bandcamp.

* Make sure it can query for multiple cities.

### Day 2

* Set up graph and implement the sizing functions for the genre representations.

### Day 3

* Create Artist List and Artist List items.

* Get tabs for subgenre's up and running

### Day 4

* Finish styling and resolve any bugs.
