# Youtube video I have been using to:

I used this youtube video to create my website:
https://www.youtube.com/watch?v=LIFvgrRxdt4

# Step by step

## To create a new site
Open a terminal and execute the command line:

```
hugo new site <name of website folder>
```

Copy a theme for website folder
"Under constructrion"

## Test a website locally

```
hugo server
```

## Maintance

### Create a new post or publication

```
hugo new publications/paper19.md
```

## Create a public folder and files for deploy

```
hugo -t PaperMod
```

## Submit modification to github reposity

Enter in the public folder:

```
cd public
```

Check the remote connection
```
git remote -v
```

Check the modifications
```
git status
```

Add commit for the modifications
```
git add .
git commit -m "Add a new publication"
```

Submit the modification
```
git push origin main
```




Enter to the nicolau-gohugo-website folder
```
cd ../../
```

Check the modifications
```
git status
```

Add commit for the modifications
```
git add .
git commit -m "Add a new publication"
```

Submit the modification
```
git push
```