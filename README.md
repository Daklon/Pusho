# Pusho
If you are a git user you probably have found the following message multiple times a day:

```
fatal: The current branch new-cool-feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin new-cool-feature
```
You normally has to copy the solution given by the error (very useful) and paste it.

Pusho is a really small tool (just two lines bash script) to make you git push life easier.

It will get your current branch and will do a git push for you with the appropiate flag, much easier and faster than copying and pasting or typing.

# Install

```
curl -LO https://github.com/Daklon/Pusho/releases/download/v1.0.0/pusho
cat pusho
sudo install pusho /usr/local/bin
```

Never install or execute anything from an internet stranger without reading the code ;)
