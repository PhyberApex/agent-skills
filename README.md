# Agent Skills

My personal collection of skills.

## Installation

### Global Install (all projects)
```bash
npx skills PhyberApex/agent-skills.git -g -a claude-code -y
```

### Project-Specific Install
```bash
npx skills add PhyberApex/agent-skills
```

### Install Specific Skill
```bash
npx skills add PhyberApex/agent-skills/skill-name
```

## Available Skills

- **do-work** - Complete one unit of work end-to-end with validation feedback loops (understand → plan → implement → validate → commit)
- **write-a-prd** - Create a PRD through user interview, codebase exploration, and module design, then submit as a GitHub issue
- **github-triage** - Triage GitHub issues through a label-based state machine with interactive grilling sessions
- **improve-codebase-architecture** - Explore a codebase to find opportunities for architectural improvement, focusing on deepening shallow modules for better testability
- **prd-to-issues** - Break a PRD into independently-grabbable GitHub issues using tracer-bullet vertical slices
- **grill-me** - Interview the user relentlessly about a plan or design until reaching shared understanding

## Tools

- **ralph/** - AFK automation tool that runs Claude in a loop to complete tasks from PRDs and issues until done

## Recommended Skills

Skills from the community that I've found helpful:

- [**impeccable**](https://github.com/pbakaus/impeccable) - Frontend design system by @pbakaus - normalize, polish, animate, and more

## Updating Skills

```bash
npx skills update
```