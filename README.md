# Breaking the Monolith by using hapi 
## Background
Let me get the disclaimer out of the way: I am not an expert on Hapi
I started looking into Hapi's ability to break components out.
This is my attempt to follow other tutorials from a hello world to a true component system.
I have broken this down into the following steps

| Project  | Description | Link |
|---|---|---|
|hapi-tut-monolith-01|A simple hello world hapi project| [https://github.com/quapaw/hapi-tut-monolith-01](github)|
|hapi-tut-monolith-02a|Add services - customers and products| [https://github.com/quapaw/hapi-tut-monolith-02a](github)|
|hapi-tut-monolith-02b|Adding Glue and externalizing config| [https://github.com/quapaw/hapi-tut-monolith-02b](github)|
|hapi-tut-monolith-02c|Moving services into their own folders| [https://github.com/quapaw/hapi-tut-monolith-02c](github)|
|hapi-tut-monolith-03-main|Moved service into own project.  This pulls the services in| [https://github.com/quapaw/hapi-tut-monolith-03-master](github)|
|**hapi-tut-monolith-03-customer**|Just the customer service| [https://github.com/quapaw/hapi-tut-monolith-03-customers](github)|
|hapi-tut-monolith-03-products|Just the produce service| [https://github.com/quapaw/hapi-tut-monolith-03-products](github)|

#HAPI Tutorial - Monolith - 3 - customers api service
Full instructions are listed in [hapi-tut-monolith-02-main](https://github.com/quapaw/hapi-tut-monolith-03-master)