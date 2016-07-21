# Pokemon-Go-Rocket-API

A Pokemon Go bot in C#

## Features
* PTC Login / Google
* Get Map Objects and Inventory
* Search for gyms/pokestops/spawns
* Farm pokestops
* Farm all pokemons in neighbourhood
* Evolve pokemons
* Transfer pokemons
* Auto Updates

## Getting Started

Go to PokemonGo\RocketAPI\Console\App.config -> Edit the Settings you like -> Build and Run (CTRL+F5)

## Transfer Types

The most popular option is probably the duplicate type that removes all duplicates and leaves you one pokemon of each type with the highest CP.

* none - disables transferring
* cp - transfers all pokemon below the CP threshold in the app.config, EXCEPT for those types specified in program.cs in TransferAllWeakPokemon
* leaveStrongest - transfers all but the highest CP pokemon of each type SPECIFIED IN program.cs in TransferAllButStrongestUnwantedPokemon (those that aren't specified are untouched)
* duplicate - same as above but for all pokemon (no need to specify type)
* all - transfers all pokemon
