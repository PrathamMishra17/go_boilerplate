# Config package overview


The config.go file typically consist of all the strong typed struct that mirrors all the setting the app needs to run in the environment,

## core responsibilities 

1.  ** Loading environement variables
    - Reading variables from .env files and from os using standard go library like viper , koanf, we are using koanf
    

## Observability file

In backend development, observabiltiy refers to the ability to understand what is happenning in the running application by inspecting it outputs via Loggs, metrics,traces and Health status
