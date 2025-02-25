# RoomLogg PRO Data Scripts

## Overview

Set of script to consolidate data from RoomLogg PRO device and create plots.

## Scripts

1. [consolidate_raw_data.py](consolidate_raw_data.md): Consolidate all backups to CSV files per room.
1. [transform_raw_data.py](transform_raw_data.md): Transform raw data into a single table and export it to a CSV file.
1. [graph_from_csv.py](graph_from_csv.md): Build a dynamic plot using plotly.

## Setup

```shell
python -m venv .venv
source .venv/bin/activate
.venv/bin/python -m pip install pip --force
pip install -r requirements.txt
```

## Current Sensor Locations

1. Living room
1. Bedroom
1. Kitchen
1. Office
1. Outdoor
