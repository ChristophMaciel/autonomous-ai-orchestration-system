# Workflow Overview

## Main Workflow Responsibilities

The orchestration system is responsible for:

- Receiving WhatsApp user interactions
- Processing conversational context
- Managing AI agent execution
- Persisting memory state
- Coordinating scheduling operations
- Querying real-time availability
- Creating calendar events
- Sending automated confirmations
- Handling cancellation flows
- Managing workflow resilience and recovery

---

## AI Agent Responsibilities

The autonomous AI agent handles:

- Conversational reasoning
- Tool invocation
- Structured output generation
- Context management
- Dynamic workflow routing
- Multi-step orchestration
- User intent interpretation
- Scheduling coordination

---

## Infrastructure Layers

### Communication Layer
- WhatsApp API
- Gmail API

### Orchestration Layer
- n8n workflows
- AI agent coordination
- Structured parsers

### Persistence Layer
- Redis memory system
- Supabase database

### Scheduling Layer
- Google Calendar integration
- Availability engine
- Reservation system

---

## Workflow Design Principles

The system architecture was designed prioritizing:

- Reliability
- Modularity
- Scalability
- Stateful orchestration
- Recovery resilience
- Real-time responsiveness
- Multi-service coordination
- Production-grade automation
