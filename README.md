# Test Case: Pip Priority Conflict - .python-version vs pyproject.toml

## Package Manager
Pip

## Python Version Detection
- **Source**: .python-version (PRIORITY #1)
- **Expected Version**: 3.8.10

## Files Present
- .python-version - 3.8.10 (SHOULD WIN)
- requirements.txt - Contains dependencies

## Test Purpose
Critical test: Validate highest priority file wins in conflict scenario.
