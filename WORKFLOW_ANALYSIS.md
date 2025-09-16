# Workflow Analysis
**What triggers this workflow to run?**
    # When the code is pushed to main branch.
**What are the four main steps this workflow performs?**
    # Get the code from the repository, validate HTML files, check for broken links, upload the built site for deployment
**What does the "checkout code" step do and why is it necessary?**
    # The checkout code downloads your repository code which is important to move on from and spearate different branches.
**What is the purpose of the environment configuration?**
    # This is important to manage the different environments and their codes, which helps to create stability within the system.
**How does this automated deployment improve reliability comparred to manual deployment?**
    # Automated deplyment improves reliability because there is less room for mistakes, doing everything manually can not only take a long time, but also has a signifficantly higher likely hood of getting messed up. automated deployment has one way of doing stuff the same everytime as long as its being fed with the correct format.
**What would happen if you pushed a code to a different branch(not main)?**
    # It would be added to that specific branch and its history, which would most likely mean that anyone who is on that branch can see it.