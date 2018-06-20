 # realitycheck-static
A sample app that reality checks some basic features on your installation of CircleCI:
1. Runs all known resource_class options
2. Read/write workspaces
3. Tests that the org-global context is working (*NOTE:* needs a key called `CONTEXT_END_TO_END_TEST_VAR` to exist in the `org-global` context)
4. Tests writing artifacts

It explicitly does not run _machine executor_ or _remote docker_ builds. If your
installation supports them, you should use the full reality check [here](https://github.com/circleci/realitycheck).

To test your installation, clone this code and add it to your CircleCI as a project.

If you have more ideas for things that should tested please submit a PR against the open source repository on [GitHub](https://github.com/circleci/realitycheck-static).

View the LICENSE file in this repository for licensing information.
