# The Music Lot

This repo contains the source code for the [The Music Lot](http://themusiclot.in/). It is a website for musicians to come together, learn, collaborate, compose and produce music.

This document covers the technical aspects of setting up the site, working on it locally and deploying to the actual site.

## Development

### Prerequisites

1. Install [NodeJS LTS](https://nodejs.org/en/). Verify by running `node -v` and `npm -v` on a command prompt
2. Install git client. I prefer using the [Windows git GUI](https://desktop.github.com/). 

### Running it

1. Clone the repo: https://github.com/shishrao/themusiclot
2. Run `npm install`
3. Run `npm install -g gulp` (If you don't have gulp already)
4. Run `gulp dev`
5. Open http://localhost:3000

All set for local dev now. Now... before committing

6. Run `gulp deploy`
7. Checkin everything except sensitive data

## Deployment

### Through an FTP client

1. Log into the ftp://themusiclot.in