# Part 1 Directory Operations
Create the following directory structure.
```
project/
├── docs/
│   ├── drafts/
│   └── final/
├── src/
│   ├── lib/
│   └── tests/
└── backup/
```

Verify this using the `tree` command 

# Part 2 File Operations

## Create the following empty files:

project/docs/drafts/outline.txt  
project/src/lib/functions.py  
project/src/tests/test_functions.py  

Create a .gitkeep file in all other empty directories.

## Copy or move the following files:

Copy functions.py to backup/  
Move outline.txt from drafts/ to final/  
Create a soft link to functions.py in docs/final/  


# Part 3 Search Operations

# Find all:  

Python files (.py extension)  
Files modified in last 10 minutes  


# Count:  

Total directories  
Total files  

# Commands you might need

```sh
mkdir   # Create directories
touch   # Create empty files
cp      # Copy files
mv      # Move files
ln      # Create links
find    # Search files/directories
ls      # List contents
tree    # Show directory structure (if available)
```
