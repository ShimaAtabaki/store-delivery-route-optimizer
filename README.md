# Store Delivery Route Optimizer

A Windows desktop application for planning a more efficient delivery sequence from one warehouse to multiple stores.

> **Portfolio showcase. Production source code is maintained privately.**

## Project origin

This project rebuilds and extends an earlier Python delivery-routing prototype created around a real multi-store delivery workflow.

The original operational problem, store/warehouse workflow, input requirements, testing priorities, and route validation were defined by **Shima Atabaki**.

## What it does

- Accepts one warehouse and up to **15 stores per run**
- Accepts store names with addresses or direct coordinates
- Calculates real road-network distance and driving time
- Finds the **exact best visit sequence** within the supported store limit
- Can optimize for shortest distance or fastest driving time
- Supports an optional return to the warehouse
- Shows the optimized road route on an interactive map
- Compares the entered order with the optimized order
- Exports the final stop sequence to CSV

## Screenshot

*A screenshot of the desktop application will be added here.*

## Why this project

The project started from a practical distribution problem: when several stores need to be served from one warehouse, the order in which they are visited can create unnecessary distance and time.

The current version turns that operational idea into a reusable desktop tool with road-network routing, exact multi-stop optimization, map visualization, and exportable results.

## Technology

Python · Windows desktop UI · OpenStreetMap/Nominatim · OSRM · Folium

## Distribution

A Windows executable is distributed separately from the private source repository.

## Project role

**Shima Atabaki** — original concept and earlier prototype, problem definition, workflow and requirements, testing, validation, and product direction.

## Status

Active refinement and testing.