# step 1 Create a new stack

pulumi stack init dev

# step 2 Run pulumi up to preview and deploy changes.

pulumi up

# step 3 Navigate to the website URL

curl $(pulumi stack output endpoint)
