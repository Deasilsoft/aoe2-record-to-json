# aoe2record-to-json

A tool used to convert AoE2 records to JSON.

## Setup

1. Clone repository.

       git clone https://github.com/Deasilsoft/aoe2record-to-json.git

2. Install mgz in project root.

       pip install mgz

## Usage

All functions are executed from `app.py`.

Available functions:

        append <record> <content>
        help
        parse <record> <command> [...]
        remove <record>

Available commands:

        completed, dataset, encoding, file_hash, hash, language, mirror, owner, platform
        restored, version, chat, diplomacy, players, profiles, ratings, teams, achievements
        duration, map, objects, postgame, settings, start_time

## Example

    app.py parse example.aoe2record players teams objects
