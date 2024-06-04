# agi-os-blueprints

To import your own blueprints and items, just add your repo to the `./extensions.json` list before you start the server with `bun dev`.

Items will have the same type as the `filename`(the "s.csv" will be removed, for example `dogs.csv => type: dog`).

You can add as many csv files to the items folder as you wish. Each row is one item.

https://github.com/agi-os/AgentFlow/blob/main/extensions.json
