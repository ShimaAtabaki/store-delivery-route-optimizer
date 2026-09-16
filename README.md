# Store Delivery Route Optimizer

A practical desktop application for planning efficient multi-stop delivery routes from a warehouse to multiple stores.

> Developed from a real warehouse-to-store distribution need in a small food manufacturing business.

## Overview

Store Delivery Route Optimizer is a Python desktop prototype designed to simplify daily delivery planning. The user provides one warehouse or starting point and a list of stores, and the application generates an efficient visiting order for the delivery run.

The project grew out of a real operational problem: deliveries from a warehouse to multiple retail stores had to be planned manually. The prototype was created to explore how a simple decision-support tool could reduce unnecessary travel and make route planning more systematic.

## Features

- One warehouse / starting point
- Up to 15 stores per delivery run
- Store input by address or geographic coordinates
- Multi-stop route optimization
- Option to return to the warehouse after the final delivery
- Route summary showing original order and optimized route
- Distance-saved and estimated-driving-time outputs
- Ordered stop list with resolved locations
- Simple desktop graphical interface

## Screenshot

*A screenshot of the desktop application will be added here.*

## Optimization Approach

The project uses a nearest-neighbor routing approach to construct an efficient delivery sequence. Starting from the warehouse, the route proceeds to the nearest suitable unvisited stop and continues until all stores have been included.

This is a practical heuristic rather than a guarantee of the globally optimal route. It is particularly useful as a lightweight approach for relatively small delivery runs, which was the original use case for this prototype.

## Real-World Context

The idea originated from a real distribution challenge in a food manufacturing and honey-packaging business. Deliveries to multiple stores required route decisions, while operational adoption also depended on cooperation from drivers and other stakeholders.

That experience made the project more than a programming exercise: it demonstrated that a technically useful system does not create value unless people are willing and able to adopt it. This practical lesson later contributed to my interest in technology adoption, organizational readiness, and digital transformation in SMEs.

## Technology

- Python
- Desktop GUI
- Address / coordinate-based location input
- Route optimization logic

## Project Status

This repository presents the project as a working prototype and portfolio project. The current version focuses on the core warehouse-to-store routing workflow rather than production-scale logistics optimization.

Potential future improvements include location search/autocomplete, map-based route visualization, traffic-aware routing, additional optimization criteria, and support for larger delivery networks.

## Author

**Shima Atabaki**

Background in Electronic Commerce, digital business, and food manufacturing, with research interests in technology adoption and digital transformation.