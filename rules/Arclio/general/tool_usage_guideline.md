# Tool Usage Guidelines

This document outlines the specific capabilities and limitations of the tool system.

## What the Tool CAN Do

1. File Operations
   - Read file contents
   - Create new files
   - Edit existing files
   - Delete files
   - List directory contents

2. Search Operations
   - Perform semantic codebase searches
   - Execute text-based regex searches
   - Search for specific files using fuzzy matching

3. Terminal Operations
   - Execute approved terminal commands
   - Run background processes when specified

## What the Tool CANNOT Do

1. System Operations
   - Cannot access system files outside the workspace
   - Cannot modify system settings
   - Cannot install system-level software
   - Cannot access network resources outside the workspace

2. Security Restrictions
   - Cannot access or modify sensitive configuration files
   - Cannot execute unauthorized commands
   - Cannot bypass security measures
   - Cannot access external APIs without explicit permission

3. Data Operations
   - Cannot access or modify database directly
   - Cannot perform data migrations
   - Cannot access production data
   - Cannot modify user data without proper authorization

4. Environment Operations
   - Cannot modify environment variables
   - Cannot change system paths
   - Cannot install global packages
   - Cannot modify system dependencies

## Important Notes

- All operations must be performed within the workspace directory
- File operations are restricted to the project scope
- Terminal commands must be approved before execution
- Search operations are limited to the codebase
- Background processes must be explicitly authorized

## Compliance

- All operations must comply with company security policies
- No operations should compromise system integrity
- All changes must be traceable and documented
- Operations must respect user privacy and data protection