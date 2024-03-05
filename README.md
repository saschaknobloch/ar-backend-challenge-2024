# ar-backend-challenge-2024
A small coding challenge for potential hires to showcase their abilities working with Rails &amp; React

## Task
First, create a simple Rails app that fetches and stores/processes data from the DND API and exposes the data through it's own API.
Second, using React, create a web app that fetches and renders a webpage with this data as a list of all items from your previously created Rails API.

1. Clone the repo
2. Create a new branch
3. Put your Rails code into the `rails-backend` folder
4. Put your React code into the `react-frontend` folder

## DND API Endpoint
Fetch and store/process data from the [/api/spells](https://www.dnd5eapi.co/api/spells) endpoint.

## Keep it simple
- On the API side, `index` action will be enough
- You can persist the spells data, cache it, or just proxy it
- No need for specs/tests, feel free to do so if it's in your standard workflow
- For the webpage, no fancy styling, pagination or whatnot is needed. A simple list of items will do
