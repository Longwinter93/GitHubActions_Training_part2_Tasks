# GitHubActions_Training_part2_Tasks
<br>Tasks is divided into first task. We need to create workflows:
<br>First workflow will be run if commits are pushed to the main branch and branches that starts with dev in their names.
<br>In addition, workflow will not be run if workflow files were edited. This workflow also will not be run if commits are pushed to another branchs than mentioned above.
<br>
<br>Second workflow will be run if a pull request is opened. It runs only for the main branch and dev branches when contributors opens pull requests. Others branches needs to be ignored.