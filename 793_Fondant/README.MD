# Fondant: Ganache-like testing environment for Casper blockchain.


## Description
As we are developing Casper blockchain apps, recently FriendlySoccer.io, we've noticed the need for an integrated testing environment. We need the Ganache equivalent in Casper Ecosystem: Quickly fire up a personal Casper network on your machine. You can run tests, explore blocks, and inspect the state while controlling how the chain operates. Everything is wrapped up in a clean and intuitive UI.

## Status

**Grant Accepted** / In progress / Completed

## Links

- DEVxDAO [Grant link]()

- casperecosystem.io[Grant link]()

- public project chat

- [Twitter](https://twitter.com/theblockbites)

## Milestones

### M1
deadline 01.05.2023

#### Description

As an effect we will deliver a roadmap with a list of possible options. We will have an electron app and ready-to-deliver nctl network package (it will probably be some dockerized container) in the repo.
We will also check if its possible to run the app on Windows OS (officially Casper do not support Windows)

#### Acceptance criteria

- Ready to implement UI
- Project skeleton
- Roadmap of functionalities


#### Reports

### M2
deadline 01.06.2023

#### Description

This version of an app should handle some basic functionalities like spinning the network from the UI, and getting the network basic config data (ports, num of blocks, last block, peers etc).

#### Acceptance criteria

- User can install the app through Electron installer
- User can control (start / stop / reset) the network from the UI
- User can browse network configuration
- User can download node operators keys

#### Reports

### M3
deadline 01.07.2023

#### Description

Basic Blockexplorer functionalities so users can browser send deploys and emitted blocks as well as see basic accounts information in the electron app.

#### Acceptance criteria

- Implemented build-in event store where you can browse all passed events (Events tab)
- Implemented Deploys view (listing all of the deploys with filtering for WASM ones or Session code)
- Filtering in every view 
- Possibility to dump the data to csv / JSON format

#### Reports

### M4
deadline 01.09.2023

#### Description

Events browser, network query possibilities and deploy creator.

Events browser so you can browse and filter events easily (which can be super handy for developers).
Possibility to query network state as well as dictionaries in an easy manner.
Deploy creator so users can create native transfer / WASM / session deploy easily.


#### Acceptance criteria

- Events view with filtering and searching capabilities 
- Query view where you can query global state (dicts, hashes etc)
- Deploy view where users can upload their WASM or run the Session code in a deploy (deploy sent that way can be monitored and the user will be notified about the changed statuses)


#### Reports

### M5
deadline 01.10.2023

#### Description

Prepare app for production + website

Run tests, check if everything is working on the following supported operating systems (MacOS, Linux, possible Windows depending of the outcome in Phase 1), prepare the deliverable for the distribution.

Create a public website with all the resources available for the end-users.

#### Acceptance criteria

- Ready to ship product
- Testing sessions
- Bugfixes

#### Reports



| Miletstone | Deadline  (DD.MM.YYYY) | Description                                                                                                                                                                                                                                                                                                              | Acceptance Criteria                                                      | Reports              |
|------------|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|----------------------|
| M1         | 01.09.2023             | As an effect we will deliver a roadmap with a list of possible options. We will have an electron app and ready-to-deliver nctl network package (it will probably be some dockerized container) in the repo. We will also check if its possible to run the app on Windows OS (officially Casper do not support Windows)   | - Ready to implement UI - Project skeleton - Roadmap of functionalities  | Link to the reports  |
| M2         | 01.09.2023             |   As an effect we will deliver a roadmap with a list of possible options. We will have an electron app and ready-to-deliver nctl network package (it will probably be some dockerized container) in the repo. We will also check if its possible to run the app on Windows OS (officially Casper do not support Windows) |  - Ready to implement UI - Project skeleton - Roadmap of functionalities |  Link to the reports |
| M3         | 01.09.2023             |   As an effect we will deliver a roadmap with a list of possible options. We will have an electron app and ready-to-deliver nctl network package (it will probably be some dockerized container) in the repo. We will also check if its possible to run the app on Windows OS (officially Casper do not support Windows) |  - Ready to implement UI - Project skeleton - Roadmap of functionalities |  Link to the reports |
| M4         | 01.09.2023             |   As an effect we will deliver a roadmap with a list of possible options. We will have an electron app and ready-to-deliver nctl network package (it will probably be some dockerized container) in the repo. We will also check if its possible to run the app on Windows OS (officially Casper do not support Windows) |  - Ready to implement UI - Project skeleton - Roadmap of functionalities |  Link to the reports |