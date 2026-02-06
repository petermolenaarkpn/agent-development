# Agent Coach - Orchestrator

## Overview

The Orchestrator Agent is the entry point to the Agent Coach system. It helps users:
- Find existing agents that meet their needs
- Understand if a new agent is necessary
- Start the agent development process

## How to Use

1. Start a conversation with "Hi" or "I need help with an agent"
2. Describe what you want to accomplish
3. The agent will search existing agents and show you matches
4. If no match, it will guide you to start creating a new agent

## Topics

- **Welcome**: Initial greeting and routing
- **Search Existing Agents**: Searches Agent Catalog for matches
- **Check Before Building**: Ensures duplicate check is done
- **Start Analyst Intake**: Hands off to Analyst Agent

## Actions Used

- SharePoint: Get items (read Agent Catalog)
- SharePoint: Create item (create Project Tracker entry)

## Knowledge Sources

- Agent Development Standards
- Quick Start Guide
- Agent Catalog (via SharePoint connector)

## Known Limitations

- Search is basic keyword matching (will improve over time)
- Cannot directly build agents, only routes and coordinates
- Requires manual handoff to Analyst Agent until that agent is built# Orchestrator Agent

