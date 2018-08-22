Aplia eZOE (fork of eZ Online Editor)
=======================================================

What is Aplia eZOE ?
-------------------

Aplia eZOE is a fork of eZOE extension which is bundled inside the eZ Publish legacy repository.

#### How to merge with eZOE

```
git clone https://github.com/ezsystems/ezpublish-legacy  
git clone git@github.com:Aplia/ezoe.git aplia-ezoe  

cd aplia-ezoe
Remove everything except .git, README.md and composer.json
cp -R ../ezpublish-legacy/extension/ezoe/ .
Review and add changes
Push and release new version
```
