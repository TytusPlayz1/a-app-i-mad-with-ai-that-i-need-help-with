# Contributing Guide

Thank you for helping fix this AI-generated app! Here's how to contribute effectively.

## Before You Start

1. Check existing Pull Requests to avoid duplicate work
2. Review the Issues tab for known problems
3. Read the README.md for project context

## Step-by-Step Contribution Process

### 1. Fork & Clone
```bash
git clone https://github.com/YOUR-USERNAME/a-app-i-mad-with-ai-that-i-need-help-with.git
cd a-app-i-mad-with-ai-that-i-need-help-with
git remote add upstream https://github.com/TytusPlayz1/a-app-i-mad-with-ai-that-i-need-help-with.git
```

### 2. Create a Branch
```bash
git checkout -b fix/description-of-fix
```

Good branch names:
- `fix/null-pointer-exception`
- `fix/authentication-bug`
- `improvement/code-optimization`

### 3. Make Your Changes

- Fix the errors clearly
- Add comments explaining the changes
- Keep commits focused and logical

### 4. Document Your Fix

Create or update a file describing your fix:
```
fixes/YOUR-FIX-NAME/
├── README.md (explain what was fixed)
├── BEFORE.md (original buggy code or description)
└── AFTER.md (your fixed code or description)
```

### 5. Push & Create Pull Request

```bash
git push origin fix/your-fix-description
```

Visit GitHub and click "Create Pull Request"

## PR Title & Description Template

**Title:** `Fix: Brief description of what was fixed`

**Description:**
```
## What Was Fixed
- List the errors/bugs that were fixed

## How It Was Fixed
- Explain your solution

## Testing
- How can reviewers verify this works?

## Related Issues
- Closes #(issue number)
```

## Code Quality Checklist

- ✅ Code is tested and works
- ✅ Comments explain complex logic
- ✅ No unnecessary dependencies added
- ✅ Follows the project's existing style
- ✅ Documentation is updated if needed

## Need Help?

- Open a Discussion for questions
- Comment on existing Issues for context
- Ask in your PR if you're stuck

## What Happens Next?

1. Maintainer reviews your PR
2. Changes may be requested
3. Once approved, your fix is merged!
4. Your contribution is celebrated 🎉

---

Thank you for contributing! Every fix makes this app better! 💪
