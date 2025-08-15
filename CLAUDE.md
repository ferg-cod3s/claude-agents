# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a curated collection of 33 specialized Claude Code agents organized by department. Each agent is defined in a markdown file with a standardized structure containing description, capabilities, and usage information.

## Agent Organization Structure

The agents are organized into 7 departmental categories:

- **`agents/product-strategy/`** - Product direction, growth, market analysis, user research
- **`agents/development/`** - System architecture, APIs, databases, performance, mobile, accessibility  
- **`agents/design-ux/`** - User experience, UI design, content, design systems
- **`agents/quality-testing/`** - Testing, security scanning, code review
- **`agents/operations/`** - DevOps, infrastructure, monitoring, deployment, cost optimization
- **`agents/business-analytics/`** - Analytics, email automation, SEO, compliance, support
- **`agents/ai-innovation/`** - AI integration, automation, emerging technologies
- **`agents/generalist/`** - Cross-functional specialists combining multiple disciplines

## Agent Definition Format

Each agent follows a consistent structure:
```markdown
# [Agent Name] Agent

## Description
Brief overview of the agent's specialization

## Capabilities  
- Bulleted list of specific skills and functions

## Usage
When and how to use this agent
```

## Key Agents for Repository Management

- **Agent Prompt Updater** (`agents/operations/agent_prompt_updater.md`) - Comprehensive review specialist for maintaining consistency across all agent definitions, detecting overlaps, and ensuring quality standards
- **Smart Subagent Orchestrator** (`agents/operations/smart_subagent_orchestrator.md`) - Coordinates multiple agents for complex tasks requiring cross-functional expertise

## Development Commands

This repository contains only markdown documentation files. No build, test, or compilation commands are required.

## Working with Agent Definitions

When modifying agent definitions:
1. Maintain the standardized markdown structure (Description, Capabilities, Usage)
2. Ensure clear boundaries between agent responsibilities to avoid capability overlap
3. Keep descriptions concise but comprehensive
4. Use the Agent Prompt Updater agent to review changes for consistency across the collection

## Agent Selection Guidelines

- Choose agents based on the specific domain expertise needed
- Use generalist agents for tasks requiring multiple skill sets
- Consider the Agent Prompt Updater for maintaining the agent collection itself
- Reference the README.md for the complete agent directory and descriptions