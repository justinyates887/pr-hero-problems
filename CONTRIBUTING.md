# Contributing to PR Hero 🦸

Thanks for helping developers level up their code review skills!

## 🎯 What Makes a Good PR Hero Problem?

**Great problems are:**
- ✅ **Realistic** - Something a real developer might write
- ✅ **Educational** - Teaches a valuable lesson
- ✅ **Testable** - Can be verified with automated tests
- ✅ **Clear** - Easy to understand what the code should do

**Avoid:**
- ❌ Trick questions or "gotchas"
- ❌ Obscure language features
- ❌ Problems that require domain knowledge

## 📝 Problem Submission Process

### 1. Check for Duplicates
Search existing problems to avoid duplicates.

### 2. Fork & Clone
```bash
git clone git@github.com:yourusername/pr-hero-problems.git
cd pr-hero-problems
```

### 3. Create Problem Structure
```bash
# Choose difficulty
mkdir -p problems/medium/your-problem-name/{csharp,javascript,python}

# Create required files
touch problems/medium/your-problem-name/README.md
touch problems/medium/your-problem-name/metadata.json
```

### 4. Fill in Required Files

**metadata.json:**
```json
{
  "id": "your-problem-name",
  "title": "Clear Problem Title",
  "difficulty": "medium",
  "categories": ["logic-error", "null-handling"],
  "description": "One-line description of what's broken",
  "languages": ["csharp", "javascript", "python"],
  "author": "yourgithubusername",
  "createdAt": "2025-11-04",
  "estimatedTime": "10 minutes",
  "learningObjectives": [
    "Understanding null reference errors",
    "Defensive programming practices"
  ],
  "tags": ["beginner-friendly", "common-mistake"]
}
```

**README.md template:** (See existing problems for examples)

**Per language:**
- `buggy.[ext]` - Code with the bug
- `solution.[ext]` - Your fixed version  
- `tests.[ext]` - Real tests using proper framework

### 5. Test Locally

**Verify tests FAIL with buggy code and PASS with solution.**

See full testing instructions in [CONTRIBUTING.md](CONTRIBUTING.md).

### 6. Submit Pull Request

Use the PR template and complete all checklist items.

### 7. Respond to Feedback

Maintainers will test your problem. Be responsive to feedback!

## 🎚️ Difficulty Guidelines

### Easy (2-5 minutes)
- Missing semicolons/syntax
- Type mismatches
- Missing imports

### Medium (5-15 minutes)  
- Off-by-one errors
- Null/undefined handling
- Simple race conditions

### Hard (15-30 minutes)
- Memory leaks
- Security vulnerabilities
- Complex race conditions

## ❓ Questions?

- Open a [Discussion](https://github.com/justinyates887/pr-hero-problems/discussions)
- Check existing problems for examples
- Tag @justinyates887 in your PR

---

**Thanks for making PR Hero better! 🦸**
