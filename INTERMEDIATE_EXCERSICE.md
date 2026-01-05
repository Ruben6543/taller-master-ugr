# Exercise Outcomes Submission Template

**Student/Group Name**: [Ruben Arturo Morales Meneses]  
**Level Completed**: [intermediate / master-of-the-universe]  
**Date**: [05/01/2026]

---

## 📋 Exercise Summary

### Exercise: [Exercise Title]
**Status**: ✅ Completed

**What I did**:
I created a new branch and midified the same file in the newbie and conflict branch to resolve conflicts, then I created a new tag

**Commands Used**:
```bash
# List the key Git commands you used across all parts of the exercise
git commit -m "Add initial file for conflicts"
git checkout feature/newbie

echo "Content from main" > conflict_file.txt
git commit -am "Modify file in newbie branch"
git merge feature/conflict-1
git tag v1.0.0

```

**Results/Output**:
```
$ git log
commit 32a3f17530ab795d77a118be22f8c4ec4545dd0c (HEAD -> feature/newbie, tag: v1.0.0)
Merge: 9effaa8 ac953a7
Author: Ruben Arturo Morales Meneses <rm372718@gmail.com>
Date:   Mon Jan 5 19:04:19 2026 +0100

    Merge branch 'feature/conflict-1' into feature/newbie

commit 9effaa8cd31ca63c2ffbbcca00eb6f49dc85f2c7
Author: Ruben Arturo Morales Meneses <rm372718@gmail.com>
Date:   Mon Jan 5 18:59:17 2026 +0100

    Modify file in newbie branch

commit ac953a7c824411cf00d61a06cc17c12564144972 (feature/conflict-1)
Author: Ruben Arturo Morales Meneses <rm372718@gmail.com>
Date:   Mon Jan 5 18:56:52 2026 +0100

    Add initial file for conflicts

commit f425e756fb8a69112d754d88f122d493df4ca22d (origin/feature/newbie)
Author: Ruben Arturo Morales Meneses <rm372718@gmail.com>
Date:   Mon Jan 5 17:35:55 2026 +0100

    added newbie description


```

**Screenshots**:
![App Screenshot](images/confLicts.png)

---

## 🎯 Key Learnings

**Main concepts I learned**:
1. How to work in different branches.
2. How to resolve conflicts
3. How to include tags and their purpose

**Skills I improved**:
- Conflicts, colaboration and control.
- Tags for updates

---

## 🚧 Challenges Faced

### Challenge 1: [Brief title]
**Problem**: Create a conflict manually and understand ow it works.

**Solution**: research.

**Commands/Approach**:
```bash
git merge feature/conflict-1

```



## 💭 Personal Reflection

**What surprised me**:
How conflicts work, and how to realise that there will be one.

**What I found most difficult**:
Create a conflict by my own.

**What I found most useful**:
Tags and solving conflicts

**How I would apply this in real projects**:
Tags for updates, versioning and control.
Conflicts if exist

---

## 📊 Self-Assessment

Rate your confidence level for each topic (1-5, where 5 is very confident):

| Topic | Confidence (1-5) | Notes |
|-------|------------------|-------|
| Basic Git commands | [5] | |
| Branching & merging | [5] | |
| Remote operations | [5] | |
| Conflict resolution | [5] | |
| History rewriting | [1] | |
| Git hooks | [1] | |
| Security practices | [1] | |

---

## 🔗 Evidence/Artifacts

**Links to branches/commits**:
- Link to your outcome branch: `https://github.com/Ruben6543/taller-master-ugr/tree/feature/newbie`
- Key commits demonstrating your work:
  - Commit hash: [Short description]
  - Commit hash: [Short description]

**Additional files created** (if any):
- File 1: conclict_file.txt


---

## ✅ Completion Checklist

Before submitting, ensure you have:
- [x] Completed the exercise for your chosen level (including all parts)
- [x] Documented all commands used with their outputs
- [x] Described challenges and how you resolved them
- [x] Provided a thoughtful reflection on your learning
- [x] Self-assessed your confidence in each topic
- [x] Pushed your outcome branch to the remote repository
- [ ] Created a Pull Request (if required by your instructor)

---

## 📝 Additional Comments

Conflicts are not important until you get one

---

**Submission Date**: [05/01/2026]  
**Ready for Review**: ✅ Yes 
