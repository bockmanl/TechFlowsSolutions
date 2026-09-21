## What triggers this workflow to run? (Look at the on: section)
    This workflow is trigger to run after coded is pushed into the main branch or a pull_request is made

## What are the four main steps this workflow performs? (List each step name)
    The 4 main steps this workflow preforms are 
        1. Get the code from the repository
        2. Validate the HTML files
        3. Check for broken links
        4. Upload the built site for deployment

## What does the "Checkout code" step do and why is it necessary?
    The Checkout code step is important because it pulls the current code in the branch (The main branch in this case), this is important because it insures that it is testing the lastest code

## What is the purpose of the environment configuration?
    The environment configuration tells Github that this is a deployment CI run instead of a normal CI run

## How does this automated deployment improve reliability compared to manual deployment?
    Having an automated deployment improves reliability by removing the chance an end user misses a step and insures that Github Actions deploys the same everytime

## What would happen if you pushed code to a different branch (not main)?
    If i pushed code into a different branch it would not deploy but it would still do its bulid and test job runs