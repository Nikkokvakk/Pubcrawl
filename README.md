# Pub Crawl Planner

A simple web application to plan your pub crawls. Features include:
- Add pubs by name and location
- Interactive Google Maps integration
- Click on map to add pubs
- Save your pub list locally
- Remove pubs from your list

## Setup

1. Clone this repository:
```bash
git clone [your-repository-url]
```

2. Get a Google Maps API key:
- Go to https://console.cloud.google.com/
- Create a new project
- Enable the Maps JavaScript API
- Create credentials (API key)
- Replace `YOUR_API_KEY_HERE` in index.html with your API key (AIzaSyCuLnDuxB2H7gayTSXHcEtu4KMPJtC59w8)

3. Open index.html in your web browser

## Usage

- Enter a pub name and click "Add" to add a pub at a random location
- Click on the map to add a pub at that specific location
- Click the × button to remove a pub from your list
- Your pub list is automatically saved in your browser

## Security Note

Make sure to restrict your Google Maps API key to your domain/localhost for security.
