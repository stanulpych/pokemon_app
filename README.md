# pokemon_app

## Name
Pokemons

## Description
Application for viewing pokemons using pokeapi made with Flutter as a task for Innowise Group.

## Architecture
Uses BloC and Clean Architecture. Dependency Injection made via GetIt. Dependency rule: inner layers are
independent of outer layers.

## Code Development rules
Code development rules are described in analysis_options.yaml and checked with Dart linter.

## Async
Asynchronous tasks are processed with Flutter Async and Dart Streams.

## Data sources
App uses pokeapi.

## Presentations abstractions
Error handling made via built-in methods and BLoC.
Navigation made with Navigator 2.0. Each Screen is wrapped in Page for better route building.

## Remote logging
Remote logging will be created with Firebase.

## Build process
TODO

## UI approach
Widgets

## Screen Structure
Navigation mechanism is Navigator 2.0. Each Screen is Wrapped in Page for better route building.

## Localization
Currently no localization exists.

## Styles and themes
Spacings are made with the step=2. E.g. spacing_1=8, spacing 1.25=10. Default theme is light.

## Supported platforms
* Android

## Project status
stopped

