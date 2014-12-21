# Yeeha
[Yeeha](http://yeeha.github.io) is a course credit dashboard for Taipei Tech student.

## Other repositories
Yeeha consists of many different sub-projects. The main ones are:

### yeeha.github.io
[yeeha.github.io](https://github.com/yeeha/yeeha.github.io) is our main Web client.
It is written using [Ember](http://emberjs.com) and communicates with [yeeha-api](#yeeha-api).

### yeeha-api
[yeeha-api](https://github.com/yeeha/yeeha-api) is the Sinatra app that's responsible for serving our API. It responds to different HTTP endpoints and runs services in [yeeha-core](#yeeha-core). Very little logic is in this repository.

### yeeha-core
[yeeha-core](https://github.com/yeeha/yeeha-core) holds most of the logic
for Yeeha. This repository is shared across several other apps and
holds the models, services, and other things that these apps need.

