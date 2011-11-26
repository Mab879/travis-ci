** extracted from the readme and outdated **

## Installation

To install your own instance of Travis you need to supply various configuration settings:


`$ cp config/travis.example.yml config/travis.yml`


In order to push these settings to Heroku you can use:

  
`$ rake heroku:config`


Starting a local worker:


`$ script/worker`


Or using God:

`
$ cp config/resque.god.example config/resque.god
$ god -c config/resque.god
`




