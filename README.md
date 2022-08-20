# How to Creat ANGULAR_JS First Project

## Prerequisites
To use the Angular framework, you should be familiar with the following:

1. JavaScript

2. HTML

3. CSS

## Install the Angular CLI
You use the Angular CLI to create projects, generate application and library code, and perform a variety of ongoing development tasks such as testing, bundling, and deployment.

To install the Angular CLI, open a terminal window and run the following command:

``` 
npm install -g @angular/cli
```

 On Windows client computers, the execution of PowerShell scripts is disabled by default. To allow the execution of PowerShell scripts, which is needed for npm global 
binaries, you must set the following execution policy

```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

## Create a workspace and initial application

1. Run the CLI command ng new and provide the name my-app, as shown here:

```
ng new my-app
```

2. The ng new command prompts you for information about features to include in the initial app. Accept the defaults by pressing the Enter or Return key.

## Run the application

1. Navigate to the workspace folder, such as my-app.

2. Run the following command:

```
cd my-app
ng serve --open
```
