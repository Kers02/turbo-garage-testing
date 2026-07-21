# 🚗 Turbo Garage Demo

Welcome to **Turbo Garage**, a training project designed to practice Git using a real-world garage inventory scenario.

---

# 📖 Story

Mr Axel owns a garage called **Turbo Garage**.

For years, he managed his inventory using multiple copies of files stored on his laptop:

- CarParts_v1.txt
- CarParts_Final.txt
- CarParts_Final_v2.txt
- CarParts_Really_Final.txt

As the garage grew, more team members started contributing to the project. Soon, nobody knew which version was the latest or who had made specific changes.

To solve this problem, Mr Axel decided to use Git.

Your mission is to help him build and maintain the Turbo Garage inventory while learning the most common Git workflows used by development teams.

---

# 🎯 Demo Objective

Throughout this exercise, you will:

- Build new features
- Share work with teammates
- Retrieve updates from GitHub
- Reuse existing work
- Organize project history
- Clean up mistakes

---

# 🚦 Demo Tasks

## Task 1 - Bring The Project To Your Laptop

### Objective

Download the Turbo Garage repository from GitHub.

### Starting Repository

```text
README.md
```

---

## Task 2 - Create Your Workspace

### Create Branch

```text
feature/car-parts
```

### Objective

Create a safe workspace where inventory development can take place.

---

## Task 3 - Build The Engine Inventory

### Create File

```text
EngineParts.txt
```

### Add Content

```text
Engine
Battery
Radiator
Spark Plug
Alternator
Fuel Pump
```

### Objective

Save the engine inventory as its own checkpoint.

---

## Task 4 - Build The Body Inventory

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

Save the body inventory separately from the engine inventory.

### Expected History

```text
Add engine parts list

Add body parts list
```

---

## Task 5 - Share Your Work

### Objective

Publish your branch so teammates can view it on GitHub.

### Expected Result

A new remote branch becomes available online.

---

## Task 6 - Update The Body Inventory

Additional body parts need to be added.

### Update BodyParts.txt

Add:

```text
Mirror
Windscreen
Headlight
```

### Objective

Update the most recent checkpoint instead of creating a new one.

---

## Task 7 - Check For Team Updates

### Scenario

While you were working, teammates added new work online.

### Objective

Check for available updates.

### Available Remote Updates

```text
Garage Notice

Turbo Garage inventory is now managed using Git.
```

---

## Task 8 - Download Team Updates

### Objective

Synchronize your local project with GitHub.

### Expected Result

Your local repository contains the latest project updates.

---

## Task 9 - Refresh Your Branch

### Scenario

The main branch has progressed while you were working.

### Objective

Move your feature work onto the latest version of the project.

### Expected Result

Your branch contains:

- Latest main branch updates
- Your inventory changes

---

## Task 10 - Integrate A Completed Feature

A teammate has already completed a service package feature.

### Available Branch

```text
feature/service-package
```

### File

```text
ServicePackage.txt
```

### Content

```text
Basic Service
Premium Service
```

### Objective

Bring this completed work into your branch.

---

## Task 11 - Reuse Existing Work

A teammate has also created an interior parts feature.

### Available Branch

```text
feature/interior-parts
```

### File

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

Bring only this change into your branch without taking the entire branch.

---

## Task 12 - Start A Maintenance Checklist

### Create File

```text
ServiceChecklist.txt
```

### Add Content

```text
Oil Change
Tyre Pressure
```

### Scenario

An urgent issue appears before the work is complete.

### Objective

Temporarily store your unfinished work.

---

## Task 13 - Improve The Branch Name

The feature now contains:

- Engine Parts
- Body Parts
- Interior Parts
- Service Packages
- Maintenance Information

### Current Name

```text
feature/car-parts
```

### New Name

```text
feature/car-inventory
```

### Objective

Choose a branch name that better reflects the feature.

---

## Task 14 - Continue The Checklist

Return to the maintenance checklist.

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

Complete and save the checklist.

---


---

## Task 15 - Oops, Wrong Change

While updating the maintenance checklist, Mr Axel accidentally adds:

```text
Replace Engine
```

### Incorrect File

```text
Oil Change
Tyre Pressure
Brake Inspection
Coolant Check
Replace Engine
```

### Objective

Remove the unwanted modification and return the file to the last saved version.

### Expected Result

```text
Oil Change
Tyre Pressure
Brake Inspection
Coolant Check
```

### Learning Point

Sometimes mistakes are made before a commit is created.

In this case, Mr Axel simply wants to discard the unwanted file changes and restore the file to its previous state.

---

# ✅ Expected Final Repository

```text
README.md
EngineParts.txt
BodyParts.txt
InteriorParts.txt
ServicePackage.txt
ServiceChecklist.txt
```

---

# 🎓 Git Concepts Practiced

| Task | Concept |
|--------|-----------|
| Bring project locally | Clone |
| Create workspace | Branch |
| Save progress | Commit |
| Share work online | Push |
| Check for updates | Fetch |
| Download updates | Pull |
| Correct latest commit | Amend |
| Update branch from latest project | Rebase |
| Integrate completed feature | Merge |
| Reuse one specific change | Cherry-Pick |
| Save unfinished work | Stash |
| Resume unfinished work | Stash Pop |
| Rename workspace | Branch Rename |
| Discard unwanted file changes | Restore |

---

# 🚀 Completion Goal

By the end of this exercise, Mr Axel will know:

> Which version is the latest,
>
> who made each change,
>
> how to collaborate safely,
>
> and how to recover from mistakes without losing valuable work.

---

**🚗 Welcome to Turbo Garage**  
*Where car parts meet version control.*
``
