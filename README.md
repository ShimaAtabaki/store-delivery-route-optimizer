# Store Delivery Route Optimizer

A prototype desktop application exploring a practical warehouse-to-store delivery-routing problem.

> **Portfolio showcase. Source code is maintained separately.**

## Project origin

This project is based on an earlier Python prototype developed from a real multi-store distribution need. The aim was to explore a more systematic way of ordering delivery stops rather than relying entirely on manual route planning.

The operational problem, delivery workflow, initial requirements, and testing were based on practical experience with warehouse-to-store distribution.

## What it demonstrates

- A warehouse as the starting point for a delivery run
- Multiple store destinations
- Store/location input through addresses or coordinates
- Generation of a suggested delivery sequence
- Comparison between the entered sequence and the suggested route
- A desktop interface for experimenting with the routing workflow

The application has been developed as a prototype and portfolio project. It should not be interpreted as a production logistics system or as guaranteeing a globally optimal route under all conditions.

## Screenshot

*A screenshot of the desktop application will be added here.*

## Routing approach

The original prototype used a nearest-neighbor approach: beginning at the warehouse, it selected a nearby unvisited store as the next stop and repeated the process until the delivery locations had been visited.

This type of heuristic is useful for exploring small routing problems, but it does not by itself guarantee the mathematically optimal route. The project is therefore presented primarily as a practical prototype and learning project rather than a commercial route-optimization product.

## Why this project

The project originated from a real distribution workflow in which deliveries from a warehouse to several stores required route-planning decisions. It also highlighted a broader practical issue: the usefulness of a digital tool depends not only on its technical design, but also on whether people and organizations are prepared to adopt it.

That experience contributed to my interest in technology adoption, organizational readiness, and digital transformation in SMEs.

## Technology

Python-based desktop prototype. Additional routing, mapping, and interface components have been explored during development.

## Project role

**Shima Atabaki** — problem identification, original prototype concept, workflow definition, requirements, testing, and project direction.

## Status

Prototype / portfolio project. Further refinement and validation are ongoing.