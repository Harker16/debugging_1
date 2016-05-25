# Debugging 1

A program to introduce you to debugging.

### Instructions

In this program, there are three bugs. You have to find them, and fix them. You have to do this as systematically as possible:

- Tighten the loop (find the _exact line_ the bug is coming from)
- Get some insight (use `p` to inspect everything in the region of that line)
- Once you know the _one thing_ that is wrong, out of place, misspelled, or not giving you what you expect, try to fix it.

> Wisest is he who tries only one thing to fix the problem. Faffing about trying whatever occurs to you next is a recipe for development hell.

### User Stories

```
As a user
So I can never be late
I want to make an appointment with a time and title
```

```
As a user
So I can see all appointments I have today
I want to print out all upcoming appointments
```

```
As a user
So I can avoid conflicts
I want to see an error if I try to book when there is already an appointment
```

```
As a user
So I can know where my appointment is
I want to add a location to my appointment
```

```
As a user
So I can know where my appointment location is easily
I want to get a human-readable string of my appointment location
```
