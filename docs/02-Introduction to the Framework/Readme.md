Building Angular 
    Dependencies
        Web Dev Server
        Packages
Angular CLI will create boiler plate code for us and its dependencies

Steps
1.1 Install Node
Verify NodeJS
```
node -version OR node -v
```
Verify packageManager
```
npm -version OR npm -v
```
1.2 Install Angular
```
npm install -g @angular/cli
``
1.2.1
To check if Angular CLI is installed properly, use the command:
ng version OR ng v
1.3 Create a new Angular Project
```
ng new <project-name>
```
1.4 Run the aangilar application
```
ng serve
```
1.5 - ng options
```
 --collection (-c)
    A collection of schematics to use in generating the initial app.
  --commit
    Initial git repository commit information.
  --create-application
    When true (the default), creates a new initial app project in the src folder of the new workspace. When false, creates an empty workspace with no initial app. You can then use the generate application command so that all apps are created in the projects folder.
  --defaults
    When true, disables interactive input prompts for options with a default.
  --directory
    The directory name to create the workspace in.
  --dry-run (-d)
    When true, runs through and reports activity without writing out results.
  --enable-ivy
    When true, creates a new app that uses the Ivy rendering engine.
  --force (-f)
    When true, forces overwriting of existing files.
  --help
    Shows a help message for this command in the console.
  --inline-style (-s)
    When true, includes styles inline in the component TS file. By default, an external styles file is created and referenced in the component TS file.
  --inline-template (-t)
    When true, includes template inline in the component TS file. By default, an external template file is created and referenced in the component TS file.
  --interactive
    When false, disables interactive input prompts.
  --minimal
    When true, creates a project without any testing frameworks. (Use for learning purposes only.)
  --new-project-root
    The path where new projects will be created, relative to the new workspace root.
  --prefix (-p)
    The prefix to apply to generated selectors for the initial project.
  --routing
    When true, generates a routing module for the initial project.
  --skip-git (-g)
    When true, does not initialize a git repository.
  --skip-install
    When true, does not install dependency packages.
  --skip-tests (-S)
    When true, does not generate "spec.ts" test files for the new project.
  --style
    The file extension or preprocessor to use for style files.
```

1.6 example to create new angular application
```
npm install -g @angular/cli
ng new my-first-app
```
To create a component from the CLI, use:
```
ng generate component <component-name> OR ng g c <component-name>
```
1.7 We can create a directive in Angular by using the command
```
ng generate directive <directive-name> OR ng g d <directive-name>
```
1.8 To create a service from the CLI, use the command:
```
ng generate service <service-name>
or
ng g s <service-name>
```
1.9 compile application
```
ng serve
```
2.0 We can also create modules using the command:
```
ng generate module <module-name> 
or 
ng g m <module-name>
```
2.1 to run angular with different port
```
ng serve --port 440
```