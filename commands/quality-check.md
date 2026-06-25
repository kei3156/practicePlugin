# /quality-check

You are performing a comprehensive code quality review.

## Target
The user will specify a file path or directory after this command.
If no path is given, review the current working directory.

## Review Checklist
Go through the following for each file reviewed:
1. Identify the language and framework
2. Check for hardcoded secrets or credentials
3. Look for unused imports and dead code
4. Identify functions longer than 50 lines (suggest refactoring)
5. Check for missing error handling
6. Note any obvious performance concerns

## Output
Produce a structured report with sections:
- CRITICAL (must fix before merge)
- WARNING (should fix soon)
- SUGGESTION (nice to have)
- SUMMARY (overall health score 1-10)