# phpBB Breizh Ajax Preview Extension

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/Sylver35/ajaxpreview/badges/quality-score.png?b=1.4.0)](https://scrutinizer-ci.com/g/Sylver35/ajaxpreview/?branch=1.4.0)
[![Build Status](https://scrutinizer-ci.com/g/Sylver35/ajaxpreview/badges/build.png?b=1.4.0)](https://scrutinizer-ci.com/g/Sylver35/ajaxpreview/build-status/1.4.0)
[![Code Intelligence Status](https://scrutinizer-ci.com/g/Sylver35/ajaxpreview/badges/code-intelligence.svg?b=1.4.0)](https://scrutinizer-ci.com/code-intelligence)

## Install

1. Download the latest release.
2. Unzip the downloaded release, and change the name of the folder to `ajaxpreview`.
3. In the `ext` directory of your phpBB board, create a new directory named `sylver35` (if it does not already exist).
4. Copy the `ajaxpreview` folder to `/ext/sylver35/` (if done correctly, you'll have the main extension class at (your forum root)/ext/sylver35/ajaxpreview/composer.json).
5. Navigate in the ACP to `Customise -> Manage extensions`.
6. Look for `Breizh Ajax Preview` under the Disabled Extensions list, and click its `Enable` link.

## Uninstall

1. Navigate in the ACP to `Customise -> Extension Management -> Extensions`.
2. Look for `Breizh Ajax Preview` under the Enabled Extensions list, and click its `Disable` link.
3. To permanently uninstall, click `Delete Data` and then delete the `/ext/sylver35/ajaxpreview` folder.

## License

[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)
