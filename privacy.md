---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy for Tilework

**Effective date:** 17 November 2026
**Last updated:** 17 November 2026

Tilework ("the app", "we", "us") is a Discord Activity of daily puzzles, made and
operated by c³d. This policy explains what the app stores, why, who sees it, how long
it is kept, and how you can get a copy of it or have it deleted.

**Contact for all privacy requests: me@noita.dev**

---

## 1. Summary

- When you open Tilework, Discord tells us **who you are** (your user ID, username,
  display name and avatar). We store that, your **puzzle plays** (progress, times,
  hints, mistakes) and the **rewards** you earn.
- Your **name, avatar, times and hints are shown to other players** in the servers and
  channels where you play: on that server's leaderboard, to people in the same voice
  channel, and in result posts. That is how the game works. The leaderboard across all
  servers only shows you if you choose to be on it.
- We **do not read or store your messages**, and we do not ask for your email address.
- We **do not sell your data**, use it for advertising, or use it to train machine
  learning or AI models.
- You can **get a copy of your data or have it deleted** at any time (section 8).

---

## 2. What we store

| Data | Why |
|---|---|
| Discord user ID, username, display name and avatar | To know who is playing, and to show your name on leaderboards and results. Refreshed each time you open the app. |
| Puzzle plays: which puzzle, your progress on the board, start and finish times, time taken, hints used, mistakes and time penalties | To save your game, time it on our clock, check your answer, and rank daily puzzles. |
| The server and channel you played in | To show results to that channel, run that server's leaderboard, and pay that server's currency if it has one. |
| Rewards: Sparks and any server currency you earn, as a list of entries | To show your balances and apply the earning limits. |
| An encrypted copy of the Discord access token you grant when signing in | To check, without our bot being in your server, whether you may change that server's Tilework settings. It is sealed with a key only the server holds and expires when Discord's token does. |
| Server settings, set by a server's managers (games on or off, hint limit, results channel, manager role, the server's own currency and its rules), and who last changed them | To run Tilework the way each server chose. |
| The ID of the daily results message the app posts in a channel | To update that one message during the day instead of posting a new one. |
| Feedback you send (from the Feedback button or `/feedback`): its type, your message, the game and server it came from, and the app version | To read it and fix or improve Tilework. A copy is posted to a private Discord channel that only the operator can see, so it is read quickly. |

When you sign in, Tilework asks Discord for three permissions: `identify` (who you
are), `guilds` (which servers you are in) and `guilds.members.read` (your roles in a
server). The last two are only used to check whether you can manage Tilework's
settings in a server. We do not store your server list or your roles.

---

## 3. What we do not store

- **Message content.** Tilework has no access to your messages and does not request
  the Message Content Intent.
- Email addresses, real names, phone numbers or payment information. Tilework has no
  paid features.
- Your IP address. Sign-in is rate limited by IP address in memory only; it is never
  written to our database.
- Voice data, presence or activity status, or server member lists. The app uses no
  privileged Gateway Intents.

---

## 4. What other people can see

Tilework is a social game, so some of what we store is shown to others:

- **Server leaderboards** show your name, avatar, time and hints to people in the
  server where you played. The **Everyone** leaderboard, across all servers, only shows
  you if you turn it on (it starts off, and you can turn it off again at any time).
- **People in the same voice channel** can see that you have a puzzle open and how far
  along you are, and once they have finished the same daily they can watch your board.
- **Result posts** in a channel show the names, times and hints of people who finished
  that day's puzzles there.
- **Server managers** can see that server's settings and who last changed them.

Result images never show the answers to a daily puzzle, only progress and times.

---

## 5. Who processes your data

We do not sell, rent or trade personal data. It is processed by:

| Provider | Role |
|---|---|
| Discord, Inc. | The platform Tilework runs on. Sign-in, avatars and messages the app posts are handled by Discord under [Discord's Privacy Policy](https://discord.com/privacy). |
| Railway Corporation | Hosts the app and its PostgreSQL database in the United States, under a Data Processing Addendum. Databases are encrypted at rest. |

We may also disclose data where the law requires it.

---

## 6. How long we keep it

| Data | Retention |
|---|---|
| Your profile, plays and rewards | While Tilework operates, so your history, streaks and leaderboard entries keep working. Deleted on request (section 8). |
| Encrypted Discord access token | Until it expires, and replaced each time you sign in. |
| Server settings | While the server uses Tilework, or until its managers ask us to remove them. |
| Feedback | Up to 2 years, so we can follow problems and ideas over time. Deleted on request. |
| Application logs | Short-lived; they rotate with the hosting provider. |

**About the alpha.** Tilework is currently in alpha. At full launch, balances, streaks
and leaderboards start fresh. The alpha's records are kept, not shown, so we can award
alpha badges and tune the game; they are covered by this policy and can be deleted on
request like everything else.

Statistics we keep beyond these periods are aggregated and contain no user IDs.

---

## 7. Legal basis

Where the GDPR or UK GDPR applies, we process personal data because it is necessary to
provide the game you chose to play, and on the basis of our **legitimate interest** in
running fair leaderboards and a working service. We process the minimum needed for
that. You may object at any time using the contact above.

---

## 8. Your rights, and how to use them

You can ask us for a copy of your data, to correct it, to delete it, or to restrict how
we use it. Email **me@noita.dev** with your Discord user ID. We may ask you to confirm
the account is yours, for example by messaging us on Discord from that account.

We respond within 30 days. Repeated or excessive requests may be refused or rate
limited. If you are in the EU or UK, you can also complain to your local data
protection authority.

**What deletion removes:** your profile, your plays, your rewards, your feedback and
your stored access token. You disappear from all leaderboards. Results already posted in Discord
channels are messages stored by Discord; the app edits them during the day they were
posted but does not keep them afterwards.

**What a copy contains:** your profile, your plays, your reward entries and your
feedback, as a JSON file.

---

## 9. Children

Discord requires users to be at least 13, or older where local law sets a higher age.
Tilework is not directed at children under that age. If you believe a child's data has
been collected, contact us and we will delete it.

---

## 10. Security

Data is held in a private PostgreSQL database with access restricted to the operator.
Connections are encrypted in transit and the database is encrypted at rest by our
hosting provider. Discord access tokens are additionally encrypted with AES-256-GCM.
Credentials are kept in environment variables, never in source control. No system is
perfectly secure, but we take reasonable measures to protect what we hold.

---

## 11. International transfers

Tilework is hosted in the United States. If you use it from elsewhere, your data is
transferred to and processed there, under the safeguards in our hosting provider's
Data Processing Addendum.

---

## 12. Changes

We may update this policy as Tilework changes. The "Last updated" date will change,
and significant changes will be announced in the app.

---

## 13. Contact

**me@noita.dev**
