# BetterCommentsSetting
---
‼️ remove first and last curly brackets before use. ‼️

ℹ️ for more information, look at `aaron-bond.better-comments` extension on vs-code.

🌐 [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

## Usage
---
Install 'Better Comments' to VS Code and open the extension settings (go to extension click on the gear icon and choose 'Extension Settings') then on the bottom of the page, click on 'Edit in setting.json'. Find "better-comments.tags" the replace everything with text from 'betterCommentSetting.json' in this git (don't forget to remove first and last curly brackets before replace). Then reload the window, and you're good to go!

‼️ adjust indentation by yourself! ‼️

## Example (use comment at the begin, '#' will be used in this example)
** space after '#' in example is not necessary **
---
| symbol    | meaning              | description                                                            |
|:----------|:--------------------:|:-----------------------------------------------------------------------|
| # !       | warning              | red text                                                               |
| # ▲       | danger               | bold white text with red background (use ALT codes 30 or Unicode 25B2) |
| # ?       | question/information | light blue text                                                        |
| # //      | deprecate/not use    | gray text and has strikethrough                                        |
| # ## todo | todo header          | bold almost black text with orange background                          |
| # #- todo | todo subheader       | bold almost black text with greenish blue background                   |
| # todo    | todo item            | orange text                                                            |
| # -todo   | done todo item       | pale orange text and has strikethrough                                 |
| # *       | hightlight           | text color in green                                                    |
| # \|      | important hightlight | bold text color in dark green and has green background                 |
| # >>      | hightlight warning   | bold text in almost black and has bright yellow background             |
| # ~       | sea                  | text in white and has blue background                                  |
| # <3      | <3                   | bold text in black and has pink background                             |
