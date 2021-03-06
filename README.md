# Pre-work - *tipCalculator*

**tipCalculator** is a tip calculator application for iOS.

Submitted by: **Nanxin Jin**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is complete:

*  User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [ ] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://imgur.com/sUH8X0Q.gif' title='tipCalculator WalkThrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

When I tried to link tip bar to the calculateTip function, it was not working. I tried to implement the project again, and it still not working. So I searched some information online, and I changed _sender:Any to _sender:AnyObject, and it works well. Also, my keyborad was always hidden at the beginning, and I really don't know why because I followed the instruction step by step. However, I changed simulator->Hardware->keyboard, and diselect connect hardware keyboard, this issue was solved.

I got this homework 2 days before, and I received an email said it will due on 15th. So I just did the basic version, I will try some extra features later.

## License

    Copyright [2017] [Nanxin Jin]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
