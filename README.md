## ﻿remove branch locally:
git branch -d dev (if it has already been pushed and merged with the remote branch)
git branch -D test (This will forcefully delete the branch even if it hasn’t been pushed or merged with the remote)

## remove branch remotely:
git push origin : dev
git push origin : test

## how to checkout another branch without commit changes:
git stach
git checkout dev

## how to list tags:
git tag

## how to delete tag locally:
git tag -d v1.0

## remotely:
git push origin : v1.0

![image](2.jpg)
