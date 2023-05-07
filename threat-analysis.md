# Phishing project
## 1: Who is our target organization?
Instructure

## 2: What is our target's mission? What are they trying to do or what are they already doing?
Provide a platform for educators to give students assignments

## 3: Identify the asset you will be attempting to steal or compromise in your attack.
Login information

### 3a: Describe how your attack will work. Identify the group you will be targeting.
I will be attempting to trick gullible students who aren't as tech-aware.

### 3b: Provide a data flow daiagram that shows the pathway between the users you intend to attack and the asset you are trying to steal.
        User             User
        login            login
        info             info
          │                │
┌──────┐  ▼  ┌──────────┐  ▼  ┌────────────┐
│Client├────►│My website├────►│Canvas login│
└──────┘     └────┬─────┘     └────────────┘
                  │
                  │
             ┌────▼─────┐
             │Login info│
             │database  │
             └──────────┘

### 3c: Provide a user workflow diagram that describes the workflow of the users you are attacking. I should be clear where the phishing attack occurs in this workflow.


### 3d: A compelling argument that (a) the phishing attack has a real chance of working and that (b) it can allow you to access your target asset.

### You may find it useful to create an attack tree, but this isn't required.


## 4: Analysis of the defenses the organization will likely have in place. In this section, you should also list how you intend to overcome/cicumvent these defenses.