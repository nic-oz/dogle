# phac-kpnet-autocomplete

## Project

### Autocomplete website/widget

#### Description
- A website that enables users to quickly find and select words from a list of suggestions, as they type.
- The list is dynamically generated from a pre-populated list of values (i.e. a dictionary file), leveraging searching and filtering.
- A large data file is required to search through - consider the best data structure for this (e.g. `.txt` or `.json`).
- Consider how implementation affects user experience and web performance (e.g. time to load and search through the data file).

#### Task

Your task is to build a site which will update as you type (an autocompleter), as per the description above.

#### Goals

1) We expect __back-end testing using tape__ (test as many components as you can) and basic __front-end testing__. Please note that we expect tests on _pure functions_ and _not_ on the router.

2) Host your project on __heroku__, [see resource](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction).

3) Use __module.exports__ and __require__ to break a single large server file into smaller modules.

4) Consider what would be a good __server file structure__ based on what we have discussed over the week.


#### Example

[Dwyl autocompleter](https://github.com/dwyl/autocomplete).