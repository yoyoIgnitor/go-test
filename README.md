I have go.mod which has reference to the go module which is in a separate repo for testing.

Current behavior
I am using versionCompatibility for renovate to pick the custom go module tag starts with module1-V* but renovate throws error message invalid-version

Expected behavior

Renovate should pick the next available custom go module tag and create a PR

Link to the Renovate issue or Discussion
(https://github.com/renovatebot/renovate/discussions/33593)
