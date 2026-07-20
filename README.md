# 🚗 Turbo Garage Demo

Welcome to **Turbo Garage**, a training project designed to practice Git concepts using a car inventory management system.

---

# 📖 Scenario

Mr Axel owns a garage called **Turbo Garage**.

His team has decided to start using Git to properly manage their project files and collaborate more efficiently.

Your task is to help Mr Axel build and maintain the garage inventory while applying common Git workflows used by software development teams.

---

# 🎯 Your Mission

Complete the following tasks throughout the demo.

---

# 1. Setup The Project

### Objective

Bring the online Turbo Garage project onto your local machine.

### Expected Result

You should now have a local copy of the repository containing:

```text
README.md
```

---

# 2. Create Your Working Area

### Objective

Create a dedicated workspace for developing the car inventory feature.

### Branch Name

```text
feature/car-parts
```

### Expected Result

All future work will be performed in this branch.

---

# 3. Create The Engine Parts Inventory

### Create File

```text
EngineParts.txt
```

### Add Content

```text
Engine
Battery
Radiator
```

### Objective

Save this work as its own checkpoint in project history.

---

# 4. Create The Body Parts Inventory

### Create File

```text
BodyParts.txt
```

### Add Content

```text
Door
Bonnet
Bumper
```

### Objective

Save this work separately from the Engine Parts inventory.

### Expected History

```text
Add engine parts list

Add body parts list
```

---

# 5. Publish Your Work

### Objective

Share your feature branch with the rest of the team through GitHub.

### Expected Result

A new remote branch becomes available online.

---

# 6. Update The Existing Inventories

The mechanics have identified missing parts.

### Update EngineParts.txt

Add:

```text
Spark Plug
Alternator
Fuel Pump
```

### Update BodyParts.txt

Add:

```text
Mirror
Windscreen
Headlight
```

### Objective

Update the existing history instead of creating additional commits.

---

# 7. Check For Team Updates

### Objective

Determine whether teammates have added new content to the remote repository.

### Expected Result

You can see if your local repository is behind the remote version.

---

# 8. Download Team Updates

### Objective

Bring the latest remote changes into your local project.

### Expected Result

Your local repository is synchronized with GitHub.

---

# 9. Merge Another Completed Feature

A teammate has completed a service package feature.

### Create File

```text
ServicePackage.txt
```

### Content

```text
Basic Service
Premium Service
```

### Objective

Combine this completed work with your current branch.

---

# 10. Reorganize Your Work

The main branch has received additional updates.

### Objective

Move your work so it starts from the latest version of the main project.

### Expected Result

Your branch contains the latest project changes while keeping your own work.

---

# 11. Reuse Existing Work

A teammate already created an interior inventory.

### Create File

```text
InteriorParts.txt
```

### Content

```text
Seat
Steering Wheel
Dashboard
```

### Objective

Bring only that specific change into your branch without taking the entire branch.

---

# 12. Start A Maintenance Checklist

### Create File

```text
ServiceChecklist.txt
```

### Content

```text
Oil Change
Tyre Pressure
```

### Objective

Work begins on the checklist but is not yet complete.

---

# 13. Put Work Aside

An urgent production issue appears.

### Objective

Temporarily store the unfinished checklist and switch tasks safely.

### Expected Result

Your working directory becomes clean while keeping the unfinished work available for later.

---

# 14. Rename The Feature

The feature now contains:

- Engine Parts
- Body Parts
- Interior Parts
- Service Packages
- Maintenance Information

### Rename Branch To

```text
feature/car-inventory
```

### Objective

Use a branch name that better reflects what the feature contains.

---

# 15. Continue The Checklist

Return to the unfinished checklist.

### Update ServiceChecklist.txt

Add:

```text
Brake Inspection
Coolant Check
```

### Final Content

```text
Oil Change
Tyre Pressure
Brake Inspection
Coolant Check
```

### Objective

Complete the checklist and save the finished work.

---

# 16. Remove Engine Management

The garage has purchased a dedicated Engine Management System.

### Objective

Remove the Engine Parts feature from project history.

### Expected Result

```text
EngineParts.txt
```

no longer exists in the branch history.

---

# 17. Remove The Checklist Feature

Management decides not to track maintenance checklists in this project.

### Objective

Move the project back to a state before the checklist feature existed.

### Expected Result

```text
ServiceChecklist.txt
```

is no longer part of the latest version of the project.

---

# ✅ Final Repository

At the end of the exercise, the repository should contain:

```text
README.md
BodyParts.txt
InteriorParts.txt
ServicePackage.txt
```

### Removed During The Exercise

```text
EngineParts.txt
ServiceChecklist.txt
```

---

# 🎓 Concepts Practiced

- Clone
- Branch
- Commit
- Push
- Fetch
- Pull
- Amend
- Merge
- Rebase
- Cherry-Pick
- Stash
- Stash Pop
- Rename Branch
- Interactive Rebase
- Reset

---

🚗 **Turbo Garage**  
*Learn Git by managing a real-world garage inventory project.*
