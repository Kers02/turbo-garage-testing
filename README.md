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

Download the Turbo Garage repository from GitHub to your local machine.

### Starting Repository

```text
README.md
```

---

## Task 2 - Create Your Workspace

### Objective

Create a dedicated branch where all inventory work will be performed.

### Branch Name

```text
feature/car-parts
```

### Expected Result

All future work will be isolated from the main branch.

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
```

### Objective

Save this inventory as its own checkpoint.

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

Save this inventory as a separate checkpoint.

### Expected History

```text
Add engine parts list

Add body parts list
```

---

## Task 5 - Share The Feature

### Objective

Publish the branch so other developers can see your work on GitHub.

### Expected Result

A new branch becomes available online.

---

## Task 6 - Correct Missing Information

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

Update the existing checkpoints instead of creating new "fix" checkpoints.

---

## Task 7 - Check For Team Updates

### Scenario

While you were working, teammates pushed new work to GitHub.

### Objective

Check whether new updates are available online.

### Available Remote Changes

A teammate updated:

```text
README.md
```

with:

```text
Garage Notice

Turbo Garage inventory is now managed using Git.
```

---

## Task 8 - Download Team Updates

### Objective

Bring the latest project updates into your local repository.

### Expected Result

Your local project is synchronized with GitHub.

---

## Task 9 - Refresh Your Feature Branch

### Scenario

The main project has progressed while you were working.

### Objective

Move your feature work so it starts from the latest version of the main branch.

### Expected Result

Your feature contains both:

- Latest project updates
- Your own inventory work

---

## Task 10 - Integrate A Completed Feature

A teammate has already finished a Service Package feature.

### Remote Branch Available

```text
feature/service-package
```

### File Included

```text
ServicePackage.txt
```

### Content

```text
Basic Service
Premium Service
```

### Objective

Combine this completed feature with your branch.

---

## Task 11 - Reuse Existing Work

Another teammate has created an Interior Parts feature.

### Remote Branch Available

```text
feature/interior-parts
```

### File Included

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

Reuse only the Interior Parts change without taking the entire branch.

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

An urgent issue suddenly appears before the work is complete.

### Objective

Temporarily put the unfinished work aside.

---

## Task 13 - Improve The Branch Name

The branch now contains:

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

Use a branch name that better represents its content.

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

Finish and save the checklist.

---

## Task 15 - Remove Engine Management

The garage has purchased a dedicated Engine Management System.

### Objective

Remove the Engine Parts feature from project history.

### Expected Result

```text
EngineParts.txt
```

should no longer exist in the branch history.

---

## Task 16 - Remove The Checklist Feature

Management decides that maintenance tracking belongs in a different system.

### Objective

Move the project back to a state before the checklist feature existed.

### Expected Result

```text
ServiceChecklist.txt
```

should no longer be part of the latest version of the project.

---

# ✅ Expected Final Repository

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

# 🎓 Git Concepts Practiced

| Task | Concept |
|--------|-----------|
| Bring project locally | Clone |
| Create workspace | Branch |
| Save progress | Commit |
| Share work online | Push |
| Check for updates | Fetch |
| Download updates | Pull |
| Update previous checkpoint | Amend |
| Integrate completed feature | Merge |
| Update branch from latest project | Rebase |
| Reuse one specific change | Cherry-Pick |
| Save unfinished work temporarily | Stash |
| Resume unfinished work | Stash Pop |
| Rename workspace | Branch Rename |
| Remove specific history | Interactive Rebase |
| Move project backward | Reset |

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
