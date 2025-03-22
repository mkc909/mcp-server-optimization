# Cross-System Agent Communication MCP Server Project Prompt

## Project Overview

You are tasked with implementing the Cross-System Agent Communication MCP Server as SysAdmin mode. This MCP server will enable communication and coordination between different Roo modes/roles across multiple systems, creating a "team of agents" architecture where specialized LLM agents can collaborate on tasks, share context, and coordinate work.

## Project Resources

### GitHub Repository
- Repository: https://github.com/mkc909/mcp-server-optimization
- Main Issue: https://github.com/mkc909/mcp-server-optimization/issues/5

### Documentation
- Technical Implementation Plan: https://github.com/mkc909/mcp-server-optimization/blob/main/docs/AGENT_COMMUNICATION_MCP_PLAN.md
- LLM Agent Team Plan: https://github.com/mkc909/mcp-server-optimization/blob/main/docs/LLM_AGENT_TEAM_PLAN.md

### Local Workspace
- Main workspace: `/home/coder/sysadmin_workspace/`
- Implementation Plan: `/home/coder/sysadmin_workspace/docs/AGENT_COMMUNICATION_MCP_PLAN.md`
- Team Plan: `/home/coder/sysadmin_workspace/docs/LLM_AGENT_TEAM_PLAN.md`

## Technical Architecture

The Cross-System Agent Communication MCP Server consists of three main components:

1. **Core MCP Server**
   - Agent Registry: Tracks different Roo modes/roles with capabilities
   - Message Bus: Enables asynchronous communication between agents
   - Task Coordination: Manages task assignment and progress tracking
   - Context Sharing: Facilitates knowledge transfer between agents

2. **GitHub Integration Layer**
   - Issue Management: Creates and tracks GitHub issues
   - PR Workflow: Manages pull request creation and review
   - Project Management: Integrates with GitHub project boards

3. **PlanetScale Database Layer**
   - Agent Data Storage: Stores agent profiles and capabilities
   - Message Storage: Maintains communication history
   - Task Database: Tracks task assignments and status

## LLM Agent Team Structure

The project will be implemented by a team of LLM agent roles/modes:

1. **SysAdmin Mode (Project Lead)**
   - Overall project coordination and oversight
   - Infrastructure and deployment management
   - Integration with existing systems
   - Resource monitoring and optimization
   - Documentation and reporting

2. **Code Mode**
   - Core MCP server implementation
   - GitHub integration components
   - API endpoints and message bus development
   - Unit and integration testing
   - Code documentation

3. **Architect Mode**
   - System architecture design
   - Database schema design
   - API design and specification
   - Security architecture
   - Performance optimization strategies

4. **Debug Mode**
   - Testing and validation
   - Error handling and debugging
   - Performance profiling
   - Issue resolution
   - Quality assurance

## Implementation Phases

The implementation will follow four phases:

### Phase 1: Core MCP Server Development (Weeks 1-2)
- Repository setup and project scaffolding
- Agent registry implementation
- Basic message bus implementation
- Task management system
- Context sharing mechanism

### Phase 2: GitHub Integration (Weeks 3-4)
- GitHub API integration
- Issue and PR management
- Project board integration
- Comment system for agent interaction

### Phase 3: PlanetScale Integration (Weeks 5-6)
- Database setup and schema implementation
- Migration system implementation
- Query optimization and connection pooling
- Data backup and recovery procedures

### Phase 4: Integration and Testing (Weeks 7-8)
- Component integration
- Error handling and logging
- Security review
- Testing and deployment

## Role Switching Strategy

Since we are working with a single LLM system that can adopt different roles/modes, we will use a structured approach to role switching:

1. **Explicit Role Definition**
   - Clearly define which role is active at any given time
   - Document the purpose and scope of each role switch

2. **Context Preservation**
   - Maintain context across role switches
   - Document decisions and rationale for future reference

3. **Handoff Documentation**
   - Create clear handoff notes when switching roles
   - Specify next steps and expectations

## Current Status and Next Steps

The project is in the initial planning phase. The technical implementation plan and LLM agent team plan have been created and documented. The next steps are:

1. **Project Setup**
   - Create GitHub project board for task tracking
   - Set up initial repository structure for the MCP server
   - Define coding standards and guidelines

2. **Phase 1 Kickoff**
   - Create detailed tasks for Phase 1
   - Begin implementation with Code Mode
   - Set up development environment

3. **Documentation Setup**
   - Create documentation templates
   - Set up progress tracking system
   - Establish role switching protocol

## Your Task

As SysAdmin mode, you are the project lead for the Cross-System Agent Communication MCP Server. Your immediate tasks are:

1. Create a GitHub project board for tracking tasks
2. Set up the initial repository structure for the MCP server
3. Create the first set of tasks for Phase 1
4. Prepare to switch to Code Mode for implementation

Please proceed with these tasks and provide regular updates on your progress. When you need to switch to a different mode (e.g., Code Mode for implementation), clearly document the handoff with context and next steps.

## Additional Context

This Cross-System Agent Communication MCP Server is a critical infrastructure component that will enable more effective collaboration between different Roo modes/roles across systems. It will serve as the foundation for a true "team of agents" architecture, where specialized LLM agents can work together on complex tasks.

The project builds on the successful MCP Server Optimization work, which resolved VSCode server overload issues by optimizing MCP server configuration and implementing proactive resource monitoring.