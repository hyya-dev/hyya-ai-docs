# FAQ

**→ [Download hYYa ai](https://hyya.com/hyya-ai.html)** · [README](../README.md) · [Changelog](../CHANGELOG.md)

## What is hYYa ai for?

Work. Ask your documents and contracts, and each answer points to the passage it came from. Turn PDFs,
invoices and schedules into Excel tables, take quantities off construction drawings into Excel, and turn any
answer into a Word, Excel or PowerPoint file. hYYa Vault does all of this offline on your own device, free
and with no account, and hYYa Cloud adds frontier models from several labs, web search and whole-library
document reading.

## What is the difference between hYYa Vault and hYYa Cloud?

They are the two engines inside the same app. **hYYa Vault** runs AI on your own device: no account, no
connection, free forever — and your own hardware sets the ceiling. **hYYa Cloud** runs frontier models
online, with no ceiling from your hardware, and the work is processed on a server. You choose, question by
question.

## Is hYYa Vault really offline?

Yes. Chat, DataLens, Studio, Quantity Surveyor, file generation and Digitize all work without Wi-Fi or mobile
data. Nothing you type, store or open reaches a server until you switch an online feature on — Web Search,
Connections or your own API key — and the app tells you what will leave before it does.

The app goes online on its own only to download a model you chose, and to fetch the public list of models when
you tap "Check for new models". On Android, the system's web view and Google's text-recognition library (which
reads scanned pages on the device) send Google their own small technical messages — never your documents or
your words.

## Do I need an account?

Not for hYYa Vault. A free hYYa Cloud sign-in is needed only for hYYa Vault's optional online features — Web
Search, Connections and the Personal Assistant — and a hYYa Cloud plan for hYYa Cloud itself.

## Which models can I use?

On your device: open models from the Qwen, Gemma and Llama families, and Apple Intelligence on Apple devices
where it is turned on — nothing to download for that one. The app recommends one model that fits your device,
and marks the ones that run on it. In hYYa Cloud: frontier models from several labs, among them Claude Opus,
Claude Fable, Grok and Gemini.

## How do I know the list of models hasn't been tampered with?

The list is public at [hyya-vault-manifest](https://github.com/hyya-dev/hyya-vault-manifest) and signed with
minisign. The app checks the signature against a key built into it and ignores any list that fails, keeping
the one it already has. Each model file is also checked against the size and checksum its host publishes
before the app calls it installed.

## Which devices does it run on?

A Mac with Apple silicon on macOS 26 or later; an iPhone or iPad on iOS or iPadOS 26 or later; an Android
device on Android 8.0 or later with a 64-bit processor. hYYa Cloud also runs in any browser at
[hyya.ai](https://hyya.ai).

## Is my data used to train models, or sold?

No. hYYa Vault keeps your chats, memories and documents on your device. hYYa Cloud conversations are never used
to train models and never sold. See [hyya.ai/privacy](https://hyya.ai/privacy).

## How much does it cost?

The app is free, and hYYa Vault is free forever. hYYa Cloud has two plans: **Cloud On-Demand**, credit packs
that never expire with nothing to renew, and **Cloud Ultra**, a monthly subscription. There is no free hYYa
Cloud plan and no trial. Current prices are on [hyya.ai](https://hyya.ai).

## How do I cancel Cloud Ultra?

Where you bought it: in your App Store or Google Play subscriptions, or on [hyya.ai](https://hyya.ai) if you
subscribed on the web. Cloud On-Demand has nothing to cancel.

## I found a bug. Where do I report it?

[Open an issue](https://github.com/hyya-dev/hyya-ai-docs/issues) here, or write to us via
[hyya.com/#contact](https://hyya.com/#contact). For a security problem, follow [SECURITY.md](../SECURITY.md)
instead — please don't post it publicly.
