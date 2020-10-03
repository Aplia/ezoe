# Aplia eZOE (fork of eZ Online Editor)

## What is Aplia eZOE ?

Aplia eZOE is a fork of eZOE extension which is bundled inside the eZ Publish legacy repository.

#### How to merge with eZOE

1. Checkout `ezpublish-legacy`

   `git clone https://github.com/ezsystems/ezpublish-legacy`

2. Checkout Aplia eZOE

   `git clone git@github.com:Aplia/ezoe.git aplia-ezoe`

3. Enter Aplia eZOE

   `cd aplia-ezoe`

4. Remove everything except `.git`, `README.md` and `composer.json`

   `ls | grep -v '.git' | grep -v 'README.md' | grep -v 'composer.json' | xargs rm -R`

5. Copy updated code from `ezpublish-legacy`

   `cp -R ../ezpublish-legacy/extension/ezoe/ .`

6. Review and add changes

   `git add .`

7. Push code and add new release
