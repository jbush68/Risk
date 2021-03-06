# Risk
A Risk game similar to CollegeFootballRisk, written in Rust

- [API](/documentation/API.md)
- [Deviations from College Football Risk's API](/documentation/DEVIATIONS.md)

# Installation
*See [/documentation/getting_started.md](/documentation/getting_started.md)*.

# Contributing

## Ringmaster

*Ringmaster* is the programme routine which determines territory ownership, MVPs, and statistics for each turn. It runs on a chron job each night. 

![Ringmaster Flamegraph](/documentation/flamegraph.svg)
Produced with [FlameGraph](https://github.com/flamegraph-rs/flamegraph).
> See the current [projects](https://github.com/mautamu/Risk/projects). Feel free to submit a pull request, and include a new flamegraph. 


## Server


*Server* is the programme routine which serves both static and dynamic content to end users. If you are experiencing an issue accessing data on the website, it is highly likely that the *Server* programme is to blame. If you would like to improve the design elements, feel encouraged. Adding functionality by pull request is similarly appreciated, but check the projects or submit a PR before undertaking the project.


> See the current [projects](https://github.com/mautamu/Risk/projects). 
