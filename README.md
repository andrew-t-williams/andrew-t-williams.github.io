# Portfolio Website

Check it out [here](https://andrew-t-williams.github.io/portfolio/)!

### Local Development Setup
* Checkout the [gh-pages](https://github.com/andrew-t-williams/portfolio/tree/gh-pages) branch of this repo
* ```bundle update github-pages``` (Optional to keep dependencies up to date)
* ```bundle install```
* ```bundle exec jekyll serve```
* Goto [http://localhost:4000/portfolio/](http://localhost:4000/portfolio/)


## Completed Projects
- [x] Eudaemonia (school project)
- [x] Moodi (school project)
- [x] Command-line program - dragon something (school project)

## Project Ideas:

#### Games:
- [ ] Chess:
  1. "physical" chess board and pieces (fluid, intuitive, looks clean)
  2. save and load game states
  3. Enforce game rules for PvP match (turns, movement rules, pawns, en passant, castling rights, move history, stalemate, win condition, 50 move limit, repetition limit)
  4. save and load match game states 
  5. AI player (API or custom algorithm)
  6. switch opponent during match
- [ ] Interactive music player
  1. keyboard visual that plays notes
  2. sound type selector
  3. record and playback
  4. grid clicker to draw a song and play it
  5. highlight keys when playing back
- [ ] Conway's game of life
- [ ] 2048

#### API & Integrations
- [ ] RMS feed
- [ ] stock viewer w/ live currency converter
- [ ] weather viewer
- [ ] popular services outage tracker (GitHub, YouTube, Facebook, Netflix, Reddit, AWS, shopify, HubSpot, NetSuite, salesforce)
- [ ] Some sort of Browser extension

#### Cloud Services 
- [ ] Something interactive running in AWS lambda, accessing a db

#### Algorithms
- [ ] Implement crypto functions/cyphers 
- [ ] physics simulator (2d sandbox?)
- [ ] Crypto wallet/simple blockchain/mining software

## Blogs
* Name/dates?/brief description
* Link to repo (with a note saying that any comments, advice, or feedback about projects is appreciated!)
* Technology used
* Architecture
* (Optional) Testing technique, fault tolerance
* (Optional) Class design, reusability
* (Optional) Design patterns - which ones are used? why you thought that pattern fit that situation. If you use a framework based around a design pattern (like Spring / Struts for Java, WPF / MVC for .NET, Knockout or Angular in javascript, to give an idea)
* In order of value: embeded in website/link to demo/demo video(embeded YouTube video, set up a demo YouTube account) /demo screenshots/repo readme (which will contain in this case instructions on running)
* Make first blog post be the technologies used for the website, as well as Todo list (pulled from readme?)
* Add technology tags to posts. use them for filtering posts, along with date order. 

## Website additions to make:
- [x] Set up local dev with Jekyll
- [x] Set up gh-pages
- [ ] Clean up front page to be a welcome page (header, sidebar, card-style blog posts)
- [ ] Subheader with quick links:
  - [ ] Add Linkd in
  - [ ] Add resume page
    - [ ] Use Latex
    - [ ] Add link to download pdf version 
  - [ ] Move 'View on GH' to subheader from where it is now
- [ ] Create project cards as 'blog posts' on main page that take you to their respective pages
  - [ ] Projects pages have a shortened header with dropdown to see main headers quicklinks
  - [ ] Discovery: Each project is a branch of this repo? Or new repo that this repo references?
- [ ] Light & Dark mode
- [ ] Have "Last Edited: month day, year" beside resume, styled like timezone
- [ ] Clean up contact links (no link image, no color, link indicator and arrow over column)
- [ ] Make it a perfect score with "Chrome Lighthouse"
- [ ] Remove contact info from SEO


### Documentation
#### Website:
* [Local Development](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)
* [Adding Content](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll)
