# Welcome to the team!

We’re glad to have you here and we hope you will enjoy your time helping us out by translating the bot into your language. We know this whole thing may seem a bit hard at first, there is definitely a bit of a learning curve, but below you can find a set of guidelines that should make this process a little bit easier.

This is just a little **quick incomplete startup guide**, a lot more information about Crowdin can be found at [here](https://support.crowdin.com/crowdin-intro/).

We highly suggest reading [Crowdin's guide](https://support.crowdin.com/online-editor/) before you start translating because it talks about all of Crowdin’s built-in translator tools that are going to make your job a lot easier!

## Getting Started with Crowdin

Crowdin has a pretty simple user interface and the more you use it, the quicker you will start getting accustomed to it. To start translating you need to select your language from [the list](https://crowdin.com/project/switchblade) and then select one of the files or choose the Translate All option at the top. Shortcut to All files with language selection can be found [here](https://crowdin.com/translate/switchblade/all/en-).

On the left side of your screen, you will see the list of strings in the file, all details about the string you are translating are displayed in the middle and right sections. Once you are done translating, hit save and your translation will get added to the list.

## Provide Quality Translation

Do your best when translating, nobody appreciates word-for-word translations, so make sure your translations sound natural and are grammatically correct.

If you feel like you need context in order to translate a string and you are unable to find it in the bot, feel free to ask for help in [our Discord server](https://support.switchblade.xyz/) \(for a quick response\) or to use the Request Context button on Crowdin. Try to make sure your suggestion doesn’t conflict with other translations before submitting it. For example if someone has translated `You need to give me the volume level!` into `Meg kell adnod a hangerőt!`, you are required to use the same term when translating the string `You need to give me a package name`, so it would look like `Meg kell adnod egy csomag nevét`.

Low-effort or machine translations are really not good. Always check your translations against the original for any missing text or other issues such as broken markdown or wrongfully placed variables before submitting them. It’s important to remain active and all contributions you make are appreciated, but remember that quality always comes over quantity.

## Voting and Why it's so Important

You should always upvote correct translations to make the proofreader’s job easier. If your language doesn’t have a proofreader, you absolutely need to vote on translations so that translation managers can approve strings, because they don't understand every language. Also, think of it as feedback for the person who made the suggestion, they will know what to improve on in the future. Crowdin has a voting mode that can be accessed from View &gt; Voting Mode, it’s a true life saver when you want to vote on many suggestions.

If you suggest a translation, you are welcome to suggest it but do not downvote other translations just because they are not yours. The downvote button should be used only for errors in suggestions, bad translations and suggestions not based on context. Abusing the downvote feature may result in removing you from the project and team.

## Start using Switchblade in your own Language

Start using Switchblade in your language on your server to notice translation errors, report them to your team or directly through Crowdin and come up with a solution!

Here's an [invite](https://invite.switchblade.xyz/) to Switchblade, so you can look at every setting, command and feature.

## Remain active and become a part of the community

Keep suggesting translations whenever you have the time. Become friends with other members of the team and a part of the [community](http://switchblade.xyz/contributors). Your contributions to Switchblade will forever be appreciated by users who only speak your language.




# Variables and markdown

The strings which Switchblade uses may contain variables, and markdown. Variables are replaced by the bot with the appropriate content, and markdown is interpreted by Discord. To learn more about Discord's markdown, take a look at [this article](https://support.discordapp.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-).

Here are some examples for strings, which contain variable(s), markdown, or both.

1. `You can do it again in \*\*{{time}}\*\*`


In this example `{{time}}` is a variable, and `*` marks at the beginning and the ending are for the use of Discord markdown. Translate everything, except the variable.

2. `You've received \*\*$t(commons:currencyWithCount, { \'count\': {{count}} })\*\* as your daily reward`


This string seems a bit more complicated. `*` marks are again for Discord markdown. The content surrounded by these marks, is a variable. You should copy that as is into the translation, do not change that. You should translate every other bit of the string.

3. `[keresendő felhasználó]`


This is not a variable and does not contain any markdown. You should translate this.

4. `\<user to kiss\>`


This is not a variable and does not contain any markdown. You should translate the content of `\< \>` marks.

5. Language changed successfully to \`{{lang}}\`!


This contains one variable `{{lang}}` and `\`` marks for Discord markdown. You should translate everything except the variable.





# Frequently Asked Questions

## Where is this sentence used?

That's a tough question but thankfully, our team is on it. On Crowdin you can check the given string's context menu for useful information, some of them even have a picture attached. Otherwise try searching for it by using the bot, or ask other translators in [our Discord server](https://support.switchblade.xyz/).

