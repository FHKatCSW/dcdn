# dcdn
Basic setup to run a dash webserver and nginx with docker-compose

## Setup

### Mac

If your a Mac user you need the following steps to bring docker to life:

Install CommandLine Tools

    xcode-select --install

Install uwsgi

    pip install uwsgi

Got to directory

    cd <YOUR_FILE_LOCATION>

Bring up Docker

    docker-compose up --build