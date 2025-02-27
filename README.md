[![Build Status](https://travis-ci.org/wevote/WeVoteServer.svg?branch=master)](https://travis-ci.org/wevote/WeVoteServer) [![Coverage Status](https://coveralls.io/repos/wevote/WeVoteServer/badge.svg?branch=master&service=github)](https://coveralls.io/github/wevote/WeVoteServer?branch=master)

### Track lines of code in all WeVote Repos

`Example https://tokei.rs/b1/{host: values: github|gitlab}/{Repo Owner eg: XAMPPRocky}/{Repo name eg: tokei}`

WebApp: [![](https://tokei.rs/b1/github/wevote/WebApp)](https://github.com/wevote/WebApp) 
<br>
WeVoteServer: [![](https://tokei.rs/b1/github/wevote/WeVoteServer)](https://github.com/wevote/WeVoteServer) 
<br>
EndorsementExtension: [![](https://tokei.rs/b1/github/wevote/EndorsementExtension)](https://github.com/wevote/EndorsementExtension) 
<br>
WeVoteCordova: [![](https://tokei.rs/b1/github/wevote/WeVoteCordova)](https://github.com/wevote/WeVoteCordova) 
<br>
Campaigns: [![](https://tokei.rs/b1/github/wevote/Campaigns)](https://github.com/wevote/Campaigns) 
<br>
cordova-plugin-googleplus: [![](https://tokei.rs/b1/github/wevote/cordova-plugin-googleplus)](https://github.com/wevote/cordova-plugin-googleplus) 
<br>
gapi-script: [![](https://tokei.rs/b1/github/wevote/gapi-script)](https://github.com/wevote/gapi-script) 
<br>
Action: [![](https://tokei.rs/b1/github/wevote/Action)](https://github.com/wevote/Action) 
<br>
Account: [![](https://tokei.rs/b1/github/wevote/Account)](https://github.com/wevote/Account) 
<br>
js-cookie: [![](https://tokei.rs/b1/github/wevote/js-cookie)](https://github.com/wevote/js-cookie) 
<br>
python3-openid: [![](https://tokei.rs/b1/github/wevote/python3-openid)](https://github.com/wevote/python3-openid) 
<br>
django-background-tasks: [![](https://tokei.rs/b1/github/wevote/django-background-tasks)](https://github.com/wevote/django-background-tasks) 
<br>
DataScience: [![](https://tokei.rs/b1/github/wevote/DataScience)](https://github.com/wevote/DataScience) 
<br>
DesignInventory: [![](https://tokei.rs/b1/github/wevote/DesignInventory)](https://github.com/wevote/DesignInventory) 
<br>
ansible-django-stack: [![](https://tokei.rs/b1/github/wevote/ansible-django-stack)](https://github.com/wevote/ansible-django-stack) 
<br>
vip-embeddable-tool: [![](https://tokei.rs/b1/github/wevote/vip-embeddable-tool)](https://github.com/wevote/vip-embeddable-tool) 
<br>


# README for WeVoteServer

This WeVoteServer repository contains a Python/Django-powered API endpoints server. We take in ballot data from 
Google Civic API, Ballotpedia, Vote Smart, MapLight, TheUnitedStates.io and the Voting Information Project. We then serve
it up to voters, and let voters Support/Oppose and Like ballot items. We are also building tools to capture
and share voter guide data.

You can see our current alpha version for recent national and some reigonal elections here:  https://WeVote.US/

To get started as a We Vote developer, <a href="https://www.clahub.com/agreements/wevote/WeVoteServer">sign the Contributor License Agreement</a>.

## Installing Python/Django API Server

To install and develop the WeVote API server, follow the instructions below based on your preferred environment. 

1. Use these [Simplified Instructions for Mac](docs/README_MAC_SIMPLIFIED_INSTALL.md) leveraging the free (and powerful) PyCharm IDE and debugger (**recommended!**) 

2. [Install directly](docs/README_API_INSTALL.md) on your Linux machine (or use WSL on Windows)

3. Use [Docker](docs/README_API_INSTALL_DOCKER.md)

## Installing We Vote Mobile Web Application (React/Flux)

The website front end application is powered by the [We Vote WebApp](https://github.com/wevote/WebApp)

We distribute the We Vote WebApp in an Apache Cordova wrapper, with some native features, to provide [iOS and Android](https://github.com/wevote/WeVoteCordova) apps.

See the iOS [We Vote 2018 Ballot, @WeVote](https://itunes.apple.com/us/app/we-vote-2018-ballot-wevote/id1347335726?mt=8) in the iTunes app store for iPhones and iPads.

See the Android [We Vote 2018 Ballot, @WeVote](https://play.google.com/store/apps/details?id=org.wevote.cordova&hl=en_US) in the Google Play store for most Android phone and tablet devices.

We also have a [ReactNative for iOS and Android](https://github.com/wevote/WeVoteReactNative) that is currently on hold.


## After Installation: Working with WeVoteServer Day-to-Day

[Read about working with WeVoteServer on a daily basis](docs/README_WORKING_WITH_WE_VOTE_SERVER.md)

If you need to test donations and have not updated your openssl and pyopenssl during install and setup, you will need
[to update your local](docs/README_DONATION_SETUP.md).

See [Instructions for Scheduled Tasks](docs/README_SCHEDULED_TASKS.md)

[How to run the WeVoteServer tests](docs/README_DJANGO_TESTS.md)

[How to run the WeVoteServer Locust Load Tests](loadtest/README.md)

## Join Us

We meet weekly on Google hangouts, and on a team Slack. Please contact Dale.McGrew@WeVote.US for more information.


