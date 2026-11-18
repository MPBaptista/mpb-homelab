# MPB Homelab Documentation

## Overview
A comprehensive documentation project for the author's personal homelab infrastructure and architecture. It includes network topology diagrams, server configurations, and operational procedures.

## Project Structure
- **`diagrams/`** — Draw.io diagrams of the homelab architecture
 - `mpb-homelab.drawio` — Main architecture diagram
 - Other diagram files for specific subsystems
- **`README.md`** — Main documentation entry point
- **`docs/`** (if exists) — Additional documentation sections
- **`diagrams/`** — Additional diagram files

## Key Systems Documented
Based on the architecture diagram, the homelab includes:
- Core networking (router, switch, firewall)
- Servers (likely: web server, database, file server, media server, NAS)
- Network services (DNS, DHCP, monitoring)
- Backup and storage solutions
- Possibly: Home automation (Home Assistant), IoT, cloud integration

## Important Conventions
- Diagrams are stored in Draw.io format (`.drawio`)
- Documentation uses Mermaid diagrams where possible
- Servers use consistent naming conventions
- Network topology is hierarchical: internet → ISP → router → switch → servers
- The diagrams include IP addressing, VLANs, and routing information

## Key Files
- `diagrams/mpb-homelab.drawio` — Main architecture diagram (primary reference)
- Other `diagrams/*.drawio` — Subsystem diagrams
- `README.md` — Overview and quick reference

## Common Tasks
- Updating architecture diagrams
- Adding new servers or services
- Documenting new network configurations
- Cross-referencing diagrams with actual infrastructure
- Generating reports from the diagrams

## Data Sources
- The diagrams are the primary data source
- May be supplemented with configuration files, logs, or other documentation
- The diagrams include labels for IP addresses, VLAN IDs, and service names

## Notes
- This is a living document that changes as the homelab evolves
- Diagrams should be kept accurate with actual network configuration
- The documentation aims to be both a reference and a design guide
- Critical systems (network, backup, monitoring) are prioritized
- The diagrams likely include: ISP connection, firewall rules, routing tables, VLAN assignments