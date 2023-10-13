# Java Application Egg

This egg is designed to run any Java application, such as a Discord Bot, REST Api, Website the list goes on...

If you're application does not start properly or is stuck on "starting" then please refer to the "Start Configuration" inside the Nests tab on Pterodactyl and edit the following to suit your needs.

```json
{
    "done": [
        "initialize",
        "initialise",
        "enabling",
        "finished"
    ]
}
```

By default i've added a few phrases that are often said when [Neptune](https://github.com/flytegg/neptune) has finished enabling to indicate that you're bot is now online.
