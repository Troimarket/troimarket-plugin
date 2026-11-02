# troimarket

Sell templates, ebooks, 3D print files, prompts, fitness programs, recipes and other digital files from your chat. No monthly fee. Your own store page.

troimarket is a marketplace for selling digital products. With this plugin, your assistant drafts a listing from a file you share or a product you describe, you confirm the price and the details, you add the file on troimarket.com, you confirm the work is yours, and the listing is live with a link and your own store page at troimarket.com/@yourname.

## What is in the plugin

- One skill, `skills/troimarket/SKILL.md`, which tells the assistant what troimarket is, the seven product types, the pricing rule (free, or $1.00 and up), the order of steps for a new listing, what it must never do, how to help without the connector, and how to coach: choosing what to sell, and sharing a listing once it is live.
- One remote MCP server, declared in `.mcp.json`: `https://us-central1-troimarket-353e7.cloudfunctions.net/mcp`. This is troimarket's own connector. It is the only address the plugin connects to.

The plugin runs no scripts, has no hooks, and fetches nothing else.

## What the connector can and cannot do

It can draft and publish listings (after you confirm each one), edit a listing's title, description, price and tags, take a listing off sale or put it back, bundle listings, change your store's bio and banner color, set your Links page, post a Creator note, search the marketplace and read troimarket's selling guides.

It cannot see or touch anything about money, change your name, password or email, or delete anything for good. Files are added by you on troimarket.com, never through the assistant. Buying always happens on troimarket.com.

## Signing in

The connector uses OAuth 2.0. When you connect, your assistant sends you to troimarket.com/assistant to sign in and allow it. It is never given your password. You can disconnect it at any time on that page. Creating an account happens on troimarket.com and is for adults only.

## Data

What the assistant does for you reaches troimarket through the connector: the listing details it drafts, the store changes and notes you approve, and the searches it runs. troimarket keeps which assistant is connected and when it was last used. Your conversation stays with the assistant's provider. Privacy policy: https://troimarket.com/privacy. Terms: https://troimarket.com/terms.

## Support

support@troimarket.com, or https://troimarket.com/faq.
