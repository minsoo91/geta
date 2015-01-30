## Why Geta?
it’s part of the full Kimono outfit http://en.wikipedia.org/wiki/Geta_(footwear)
as a webscraper, the name sounds like “get-a”, which is what it does

## What is Geta?
Geta is an open source web application that makes it trivial for users to build their own single page web scrapers. Geta’s simple and attractive interface provides users with an easy way to define the fields to scrape, save the resulting scrape pattern & the data scraped from that pattern, and share the patterns they’ve created with others. 

## The Roadmap (in progress)

What happens when a user scrapes a page:
User inputs url
Target site is loaded in iframe
onClick in the iframe…
Get the css selector of the element
Highlight other elements that match the selector
Await user confirmation of selector (method undecided)
Repeat step 3 until user is finished making selections 
Allow user to name selection fields
Save the selection pattern
Associated with the user and the domain
Scrape the page per the pattern (client side for now, fuck IE), output data in JSON

## Additional Features:
User can view their saved patterns
User can view historical data scraped using each pattern
Patterns can be reused trivially 
Patterns can be made public
User can find/search/user public patterns from other users

# Development Resources:
Trello https://trello.com/b/CbQZWQ2N/development
SuperSelector. We’ll be borrowing some of their code to generate the css selectors for selected elements http://blog.caplin.com/2013/02/26/superselector-a-javascript-gui-tool-to-generate-css-selectors/

