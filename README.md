## What is this?

This is a URL shortner that redirects to Skyozora dungeon links.

## Why?

* Because Skyo links are very long, and Discord character counts include URL lengths. We want less pagination to happen in menu embeds in Discord.
* Also, this Skyo urls aren't *quite* deterministic; therefore, we do some logic here of figuring out what the correct URL is. Once we've figured that out (by pinging their servers, which is slow), we cache the result forever.

## It's not giving me the right result. Help!

Sorry about that! Let us know via the `^feedback` Tsubaki bot command, or in the Tsubaki discord server: https://discord.gg/QCRxNtC