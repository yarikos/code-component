# code-component

> A code component for the [elastic.io platform](http://www.elastic.io "elastic.io platform"), runs a piece of synchronious JavaScript inside your integration flow.

This is an open source component to run a code inside your integration flow and is developed specifically to run on [elastic.io platform](http://www.elastic.io "elastic.io platform"). You can clone it and change it as you wish. However, **if you plan to deploy it into [elastic.io platform](http://www.elastic.io "elastic.io platform") you must follow sets of instructions to succseed**. 

> **PLEASE NOTE:** This purpose of this component to test pices of JavaScript code within your integration process. This component can help the development of your own component, however, it may not be suitable for every use case. **It is not a replacement for a real component, rather than a tool to test the functionalities before adding them into your component.** 

## Before you Begin

Before you can deploy any code into our system **you must be a registered elastic.io platform user**. Please see our home page at [http://www.elastic.io](http://www.elastic.io) to learn how. 

> Any attempt to deploy a code into our platform without a registration would fail.

After the registration and opening of the account you must **[upload your SSH Key](http://docs.elastic.io/docs/ssh-key)** into our platform. 

> If you fail to upload you SSH Key you will get **permission denied** error during the deployment.

## Getting Started

After registration and uploading of your SSH Key you can proceed to deploy it into our system. At this stage we suggest you to:
* [Create a team](http://docs.elastic.io/docs/teams) to work on your new component. This is not required but will be automatically created using random naming by our system so we suggest you name your team accordingly.
* [Create a repository](http://docs.elastic.io/docs/component-repositories) where your new component is going to *reside* inside the team that you have just created. For a simplicity you can name your repository **code-component** or **code*.

```bash
$ git clone https://github.com/elasticio/code-component.git code-component

$ cd code-component
```
Now you can edit your version of **code-component** component and change according to your needs - that is if you know what you are doing. Or you can just ``PUSH``it into our system to see the process in action:

```bash
$ git remote add elasticio your-created-team-name@git.elastic.io:code-component.git

$ git push elasticio master
```
Obviously the naming of your team and repository is entierly upto you and if you do not put any corresponding naming our system will auto generate it for you but the naming might not entierly correspond to your project requirements.

![image](https://cloud.githubusercontent.com/assets/464220/10952661/3548b410-8344-11e5-811c-06702ea49cfd.png)
