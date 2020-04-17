# Personal Site, refactored and updated July 2019

## Setup instructions

1. Make sure [Ruby](https://rubyinstaller.org/downloads/) is installed correctly: ```ruby -v``` (Ensure PATH variable contains the ruby bin folder)

2. If Bundler is not yet installed, run: ```gem install bundler```

3. Install packages: ```bundle install```

4. Make sure jekyll is installed correctly:  ```jekyll -v```


## Development instructions

1. To serve locally:  ```bundle exec jekyll serve```

2. To add a project:

    - Add an entry to _data/projects.json
    - Add a folder to assets/img/projects, named with the new project's id
    - Add image files, including thumb.png, to this folder
    - Add colour variable to _sass/base/_variables.scss and use it in _sass/modules/_colour.scss
    - Add a details page to the 'project' folder
