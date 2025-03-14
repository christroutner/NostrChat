# NostrChat

dev-2024 is a branch from 2024. It was 98 commits behind the upstream on 3/14/25.
I was not able to get this branch to comile and run due to errors that were complaining that I had a newer version of Typescript.

I'm saving this branch before I sync with upstream. I also need to look at what's running on the psfoundation server to see what version of node.js it's using and which commit its
on, and which version of Typescript its using.

-----

<img src="public/logo192.png" width="100">

NostrChat is one of the most decentralized chat apps ever built. 

NostrChat is built on Nostr, and therefore doesn't rely on any centralized servers, just Nostr relays. Everyday users of NostrChat can immediately benefit from Nostr’s decentralized network. Power users can choose to further decentralization by running their own NostrChat client or Nostr relay. 

Our ReadMe is a summary about NostrChat, what it looks like, and how to use it.

[Join NostrChat](https://www.nostrchat.io/)

## What is Nostr?

[Nostr](https://github.com/nostr-protocol/nostr) is a simple open protocol for creating censorship-resistant global networks.

## How to log into NostrChat

From the [Nostrchat.io](https://www.nostrchat.io/) homepage choose one of the following:

**Create Nostr Account** (easiest option for first time users) — Click the button to “Create Nostr Account.” Instantly you’ll be given a new Nostr account. Once you login, it is highly recommended that you go to “Settings -> Keys” and save both your public and private keys. These keys are your access to your Nostr account, and you will need them again in the future.

**Use NIP-07 Wallet** (recommended for return users) — Choose the button “Use NIP-07 Wallet.” Install the Alby wallet browser extension. Once you install Alby you will be able to log into NostrChat. The benefit of the NIP-07 login is that you will manage your private keys locally in the Alby extension.

## How to use NostrChat

Once you enter NostrChat you can chat in the global chat, or create your own chat channel where you can invite others.

## How to run NostrChat locally 

Install dependencies
```bash
$ yarn 
```

Start 
```bash
$ yarn start
```

NostrChat will open in your browser.

## Roadmap 🛣️

- Mute user & Hide message ✅
- Reply in Thread ✅
- Muting ✅
- Reactions ✅
- Channel invitations ✅
- User profiles ✅
- Mentions ✅
- Channel & DM unread indicator ✅
- iOS app
- Notifications (push/fetch)
- Android app
- NIP-29 support
