![Create New CLI](http://i.imgur.com/fz12yVT.png)

### CLI Project Generator

With the rise in the popularity of projects like Create React App, Angular CLI, and Ionic CLI, as well as the productivity these clis bring to the table, there should be an easy way for developers to create their own CLI using boilerplates and also to introduce them to the world of CLI creation.

This project will allow developers to easily and quickly create CLIs that give them the most basic functionality in just a few seconds, and publish their projects to npm for users to install and start using right away.

### Check out this video walkthrough that will show you how to create a new CLI using create-new-cli
[![](http://i.imgur.com/F7fx2c6.png)](https://www.youtube.com/watch?v=gSZGWQS8aZ0)

## To create and publish your own CLI:

1. Install create-new-cli globally   
```
npm i -g create-new-cli
```

2. Create a new cli following the commmand prompts by running the create-new-cli command   
```
create-new-cli
```

##### In the above step, we will create a name and a command for our cli. The name will be the folder created for our project, and the command will be what the application is registered as in the npm registry, which will be the name field in our newly created package.json.

##### We will reference these two items as `<YourProjectName>` and `<your-project-command>` in the following steps.

3. CD into newly created project directory   
```
cd <YourProjectName>
```

4. Publish to npm (or link to test locally)   
```
npm publish OR npm link
```

5. Install new cli globally on your own machine (skip this step if you ran npm link)    
```
npm i -g <your-project-command>
```

6. Create new application using your new CLI   
```
<your-project-command> MyAppName
````

