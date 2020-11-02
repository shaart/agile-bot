# Status
| Badge | Master | Dev |
| ------ | ------ | --- |
| Build | [![Build Status](https://travis-ci.com/shaart/agile-bot.svg?branch=master)](https://travis-ci.com/shaart/agile-bot) | [![Build Status](https://travis-ci.com/shaart/agile-bot.svg?branch=dev)](https://travis-ci.com/shaart/agile-bot) |
| Quality Gate | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=shaart_team-f-discord-bot&metric=alert_status)](https://sonarcloud.io/dashboard?id=shaart_team-f-discord-bot) | - |
| Code Coverage | [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=shaart_team-f-discord-bot&metric=coverage)](https://sonarcloud.io/dashboard?id=shaart_team-f-discord-bot) | - |

# About
An agile bot that can use pluggable commands.
- Developed on OpenJDK11.
- Supported Java: 11+. 

# How to build
1. Build the application.
```shell script
./gradlew build
```

# How to run
1. Build the application.
2. Run the application.
```shell script
java -jar ./agile-bot-core/build/libs/agile-bot-core-<version>.jar
java -jar -Dagile.bot.discord.token="<TOKEN>" ./agile-bot-adapter/build/libs/agile-bot-discord-adapter-<version>.jar
```
