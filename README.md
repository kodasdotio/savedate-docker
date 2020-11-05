# Full-Stack Docker-Deployment for SaveDate.io

## Summary

Registry for full-stack-deployment for [SaveDate.io](https://github.com/orgs/CodeCraftStudios/projects/1), further described down below.

## Description

SaveDate.io is a system for creating digital representations of private or public real-world events that serve as invitations and facilitate guest list management.
Registered users are able to see an overview of events they want to attend or already have attended in the past.

The first version of SaveDate.io offers support for private events. An event (e.g. a birthday party) can be created containing general information like location and date. The creator (“inviter”) can send out special links, which act as invitations to the event, to any of his personal contacts (“invitees”) via a messenger of his choice. Invitees can use the received invitation link to view the created event and display if they are planning on attending the event or not without signing up for any service or downloading any software. Additional features like shared shopping lists complement the service.

After dominating the private event space the next step is to use SaveDate.io to create public events (e.g. a concert of a local rock-band). Public events can be distributed via event links that enable viewers to see all event information and enable SaveDate.io-users to indicate if they are planning to attend the event. With public events we will introduce more social network like features to transform the platform into a competitor to facebook public events. We aim to become the goto platform for events of any kind. SaveDate.io is intended to be a one stop service ranging from the initial first discovery of an event, buying tickets and viewing photos after the event.

## Authors

After successfully finishing a university project the mentioned above decided on sticking together as a development team and starting a real-world project

* [Markus Hinkel](https://github.com/markush97)
* [Christoph Bogner](https://github.com/svchostdotexe)
* [Thomas Stimakovits](https://github.com/stimitom)
* [Michal Kiran-Huber](https://github.com/michaelkhuber)

## Usage

First copy the environment-template into a .env file and set the options accordingly

```bash
cp .env.example .env
```

Then start the application

```bash
docker-compose up -d
```

To View the logs

```bash
docker-compose logs
```

and stop the application with

```bash
docker-compose down
```

## Documentation

Better code documentation can be found [here](https://doc.savedate.io/)