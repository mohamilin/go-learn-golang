# Documentation
 `This documentation about learning golang`
 `you can read or create issue in this repository`

# Step by step
## Initial setup 
1. Create a repo by name <strong>go-learn-golang</strong>
2. Create a folder <strong> learn-golang </strong> and execute on terminal : <strong> go mod init github.com/mohamilin/go-learn-golang </strong>. 
    - Note : 
        - github.com/mohamilin/go-learn-golang is my repo, use your repository for init the module
        - success message : <strong> go: creating new go.mod: module github.com/mohamilin/go-learn-golang </strong>

## Create module (simple module)
1. Create a file go_learn.go
    - we just create a function GoLearn (for public, first word must UpperCase)
    ```go
    package go_learn
    func GoLearn() string {
        return "Go Hello"
    }

    ```
## Create version
1. run in command / terminal : 
    - git tag  name_version (example : git tag v1.0.0)
    - git push origin name_version (example : git push origin v1.0.0)