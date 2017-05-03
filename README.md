# samwise
A series of scripts to make managing complex git repo/submodule interactions to prevent the headaches of everyday submodule interaction.

Todo
1. initial clone/creation script
 * fetches everything from necessary remotes
 * builds deps. RN will just use stack for this
 * eventually support non haskell builds

2. check in script 
 * check for changes in any submodules
 * commit and push those changes into remote
 * scale to parent and commit the change of head
 * push changes in parent incl. change of submodule head

