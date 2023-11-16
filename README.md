# BetterCommentsSetting
---
‼️ remove the first and last curly brackets before use. ‼️

ℹ️ for more information, look at `aaron-bond.better-comments` extension on vs-code.

🌐 [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

## Usage
---
Install `Better Comments` for Visual Studio Code. To access the extension settings, navigate to the extension and click on the gear icon. Select `Extension Settings` from the menu. Scroll to the bottom of the page and click on `Edit in settings.json`. Locate the property `better-comments.tags`. Replace the existing content with the text from `betterCommentSetting.json` in this repository. Remember to remove the first and last curly braces before pasting the text. Reload the VS Code window to apply the changes.

‼️ adjust indentation by yourself! ‼️

## Example (use comment at the begin, '#' will be used in this example)
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
| # tc      | todo item cont.      | orange text                                                            |
| # -tc     | done todo item cont. | pale orange text and has strikethrough                                 |
| # tb      | todo list border     | orange text and background                                             |
| # *       | highlight            | text color in green                                                    |
| # \|      | important highlight  | bold text color in dark green and has green background                 |
| # >>      | highlight warning    | bold text in almost black and has a bright yellow background           |
| # ~       | sea                  | text in white and has blue background                                  |
| # <3      | <3                   | bold text in black and has pink background                             |
