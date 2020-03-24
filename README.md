# cases_web
This will include the cases web page based on jekyll

## Development Installation
To install it locally:

First some extra tools need to be installed:

```sudo apt-get install build-essential patch ruby-dev zlib1g-dev```

1. install the ruby gems [jekyll (instructions)](https://jekyllrb.com/docs/installation/) and bundler - ```gem install bundler```
2. clone this repository - ```git clone https://github.com/CASES-LU/cases_web.git```
3. run ```bundler install``` to install all dependencies for the project.

Make it nice!!!

## Update dependencies:

To update the dependencies - if they have a new version - just call ```bundler update```. It is good practice to do that regularly anyways...

## Deploying or Developing/Testing

To start the development server: ```bundler exec jekyll serve```

If only a build is needed: ```bundler exec jekyll build```
