# gitworkflow

This is a simple github workflow for my project which contain the main branches: 

1. Main branch - contains the main source code of head and is the production ready state.

2. Develop branch - reflects the latest development delivered changes for the upcoming release. Changes in this branch are merged back to the master branch.

3. Feature branch - branches off from and merged back to develop branch. In this branch new features are developed for future releases. This branch exist in the developer repos only.

4. Release branch - branches off from develop and master branches. Reflects the desired state of a new product release.

5. Hotfix - branches off from master. Merges back to develop and master. Similar to release branch, arises from the the need to act immediately upon an undesired state of a live production version.

![gitworkflow](https://user-images.githubusercontent.com/52337688/64579166-82140680-d347-11e9-932b-a0610d514cf3.jpg)

