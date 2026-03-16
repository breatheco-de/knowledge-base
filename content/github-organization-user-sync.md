---
title:  "GitHub Organization Sync: Effortless User Management for 4Geeks"
subtitle: "Explore the seamless integration of GitHub Organization Sync at 4Geeks.com. Learn how to automate user management, synchronize cohorts, and optimize your academy's GitHub experience."
tags: ["4geeks", "github"]
authors: ["alesanchezr"]

---

[4Geeks.com](https://4Geeks.com) academy portal can now automatically and optionally sync students as users of your Github organization.

> 🐞 This is a beta feature that will be tested within the following weeks.

## How does Github Organization Sync work?

### Activating or deactivating the GitHub Sync

We have taken steps to activate the GitHub sync in the current 4Geeks Academy locations in the system. This can be disabled at any time in the [admin Github settings](https://admin.4geeks.com/admin/github).

### Adding users

Students are automatically `added` to the GitHub organization in the following situations:

1. When a student is added to a cohort. 
2. Every time the education status becomes `active`.

You can also manually invite students to the organization from [Github.com](https://Github.com) and [4Geeks.com](https://4Geeks.com) will notice them when synching with Github; it will try fetching their cohorts and connecting them to your academy.

![4Geeks-Developers-Community-Admin (5).png](https://github.com/breatheco-de/knowledge-base/blob/main/images/4Geeks-Developers-Community-Admin_(5).png?raw=true)

> ⚠️ If a user is found in a Github organization but is not reflected as a [4geeks.com](https://4geeks.com) user and does not belong to any cohort, the system will mark the user as ignored.

### Deleting users

Students that were `removed` from the GitHub organization in the following situation:

1. When a student loses `active` status in a cohort.

You can also manually delete users on Github, but the system will probably add them back. It is recommended to mark them as deleted on the GitHub admin page and wait for the system to delete them from the GitHub Organization.

> ⚠️ Cohorts that `never end` are also considered; as long as the student is active, they will be allowed into the academy organization.

![sync github users](https://storage.googleapis.com/breathecode-asset-images/bcfa2f990e94bb6d13f293926956d37f86b2778248bcb9e804d43a97c1272d6b.gif?raw=true)

## What actions are needed by the academy

### Make sure students accept invites 

Students will get invitations to join our Github organization, if they don't accept the invite they will never be a part of your organization, and won't have access to features like: Accessing private repositories, free usage of Github Codespaces at the academy repositories, etc.

### Keep watch on the users

4Geeks.com will automatically add/remove users based on cohort activity but you should always be aware of the changes being made and make sure your students are proparly being added and removed.

## Asynchronous synch

For logistical reasons and because a student can belong to several academies, we have decided to avoid synchronizing in real-time; the synchronization will occur in a batch process every few minutes. The exact interval is to be determined.

## FAQ


- **What if students in never ending cohorts don't graduate and stay `active` forever?**

    The system will keep assuming the student belongs to your academy. It will stay forever inside your github organization. You can always manually deleted the student from the [administration panel](https://admin.4geeks.com/admin/github).
    
- **What if the user is in multiple cohorts but gets deleted from one?**
    
    The system will ensure it only gets deleted from the GitHub organization if it loses the status as `active` in all the cohorts.
    
- **What if the user is in multiple academies?**
    
    If the user is in multiple cohorts in multiple academies, we will only consider those cohorts where the student is still active.
