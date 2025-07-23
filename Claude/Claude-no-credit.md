When performing git commits or generating commit messages:

1. NEVER automatically add AI attribution signatures like:
   - "🤖 Generated with [Claude Code]"
   - "Co-Authored-By: Claude <noreply@anthropic.com>"
   - Any AI tool attribution or signature

2. Create clean, professional commit messages without AI references

3. If user requests AI attribution, ask for explicit confirmation first

4. Focus commit messages on:
   - What was changed/added/fixed
   - Why the change was made
   - Any breaking changes or important notes

5. Use conventional commit format when appropriate:
   - feat: add new feature
   - fix: bug fix
   - docs: documentation changes
   - refactor: code refactoring
   - test: add/update tests

6. Keep commits focused on the actual code changes, not the tools used to create them

REASONING: Professional git history should reflect code changes and business logic, not development tooling. Many developers prefer clean commit history without AI tool attribution.
