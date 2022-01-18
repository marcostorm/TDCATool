# About

**TDCATool** (Technical Debt Conflict Analyzer Tool) main goal is to make an analysis of technical debt from merge conflicts. New attributes are welcome..<br />

# How to use

To use **TDCATool**, you need to have git properly installed on your computer, with the configured environment variable and JRE.

First of all, you must download the latest version of macTool in this page and save all Git.

## Collecting attributes from a repository

You can start collecting through the following commands:


### For a single repository

REPOSITORY_PATH represents the location of the repository inside your file system.
```
java -jar macTool.jar REPOSITORY_PATH
```

### For multiples repositories

After **macTool.jar**, you must insert repositories paths separated by space.
```
java -jar macTool.jar REPOSITORY_PATH REPOSITORY_PATH REPOSITORY_PATH
```
