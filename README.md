# react-native-deployment-example

This is an example repo to demonstrate how to setup a powerful, single-command deployment process. It was created with `react-native init`, and then edited by following the tutorial in the following blog series:

[Automate React Native Deployment](https://timmywil.com/blog/Automate-React-Native-Deployment-Part-1/)

Deployment is done with a single command:

```
$ yarn release
```

This will analyze commits, generate release notes, update versions (including iOS and Android versions), commit, tag, push, publish release notes, verify in CI, build, deploy to the app stores, and post a notification in slack.

This is a real app hooked up in TestFlight and Google Play, but it can only be deployed by those with commit access to this repo.

For a tutorial on how to accomplish this deployment flow, see the blog post above.
