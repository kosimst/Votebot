# Votebot
CLI for requesting an URL on multiple threads with rotating IPs using TOR

## What does it do?

Votebot uses your local tor client to request a given URL. You can also run multiple TOR instances and create a bot with each of them. This way you can e.g. vote an online survey a given count of times. With the help of tor each request will be handled with a different IP.

## Technical Background

Votebot connects to TOR via SOCK5 and uses curl for the requests. For the multithreading `cluster` is used.

## Usage

> Note: As the Votebot is not yet published, usage will be added
> You will be able to use as CLI as well as import it as npm module and use it in your script.
