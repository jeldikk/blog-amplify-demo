# Nextjs Amplify Demo project

I just wanted to understand how different phases of amplify commands would make effects on folder structure of the project.

Different amplify commands we will use during the process are:

<br >

**Configure amplify-cli with user profile, region and access Id's and secure keys**

```sh
$ amplify configure
```
the above command would not impact any folder structure of the project. this would have some impact on the credentials file in user profiles.

we are setting up an extra set of commands to configure our project with tailwind css.

#### Now we are going to execute amplify command to configure project( most awaited process )

```sh
$ amplify init
```

and enter all the questions asked in the prompt and give it some time to initialise amplify project. 

After this command, it will create new folder called amplify and adds files are to be ignored into `.gitignore` file. 


**install necessary aws-amplify package and ui react library**
this will add `aws-amplify` and `@aws-amplify/ui-react` to package.json dependencies list ready to be used in the project.


