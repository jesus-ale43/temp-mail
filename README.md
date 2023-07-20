<img width="150" height="150" align="left" style="float: left; margin: 0 10px 0 0;" alt="TempMail Logo" src="https://raw.githubusercontent.com/jesus-ale43/temp-mail/master/assets/tempmail_logo.png">

# TempMail
A simple Discord bot that generates you a temporary email address :)

[![](https://img.shields.io/badge/%40sapphire%2Fframework-4.5.0-blue.svg?logo=npm)](https://www.npmjs.com/package/@sapphire/framework)
[![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)
[![Support Server](https://img.shields.io/discord/783813289129672765?label=Discord&logo=Discord)](https://discord.gg/YTDm2SdeRJ)

## What is TempMail?
TempMail is a bot where you can create a temporary email address, receive and read real email messages, convert them to images, export them to formats such as text and HTML, all through Discord.

## How it works?
TempMail utilizes the API of the website "[1secMail.com](https://www.1secmail.com/api/)" to generate email addresses and receive messages through its SMTP server. Here's a step-by-step breakdown of how to use TempMail:

* ``/create <alias> <domain>``:
The first step to using TempMail is to employ the "/create" command. When executed in Discord, the bot generates a temporary email address for the user. This email address can be used to receive messages and communications without revealing the user's personal email address.

* ``/delete``:
When the temporary email address is no longer needed, users can use the "/delete" command to remove it. Executing this command deletes the email address FROM OUR DATABASE, meaning that in the "[1secMail.com](https://www.1secmail.com/api/)" system, this address will remain active, and any messages received will be deleted after one hour. Once the email address is deleted from our database, any other TempMail user may use the same email address.

* ``/inbox``:
The "/inbox" command allows users to access the inbox of their temporary email address. When executed, the bot provides users with a list of the latest messages received at that temporary email address. This function enables users to read and review important messages sent to their temporary address.

* ``/message <message>``:
With the "/message" command, users can select a specific message from their inbox and read its complete content. The bot displays the sender, subject, and content of the selected message, also providing functions for exporting it in image or text formats.
