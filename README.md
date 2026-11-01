<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./icon-dark.png" />
    <img src="./icon-light.png" alt="WhatsApp" width="144" />
  </picture>
</p>

<div align="center">

# WhatsApp

</div>

Connect WhatsApp Personal or WhatsApp Business (Cloud API) to a Ryu agent or team from a native workspace tab.

> **The public home of `ryu-whatsapp`.** Source, builds, and releases live here —
> binaries for every platform are attached to each release.
>
> This tree is generated from the Ryu monorepo, so commits pushed here
> directly are replaced on the next sync. **Pull requests are welcome** —
> open them here and they are ported into the monorepo, then flow back out.
> Ryu as a whole: https://github.com/amajorai/ryu

## Install

**App:** [Install](ryu://apps/@ryu/whatsapp) (opens the Ryu desktop app and asks you to confirm)

**CLI:**

```bash
ryu apps add @ryu/whatsapp
```

## Source & build

This is the **source of record** for the app UI. It imports Ryu's private
`@ryu/ui` design system, so it does **not** build standalone outside the
monorepo — it **builds inside the amajorai/ryu monorepo workspace**.
The shipped bundle is the built artifact, produced by the monorepo build.

## License

Apache-2.0 — see [LICENSE](./LICENSE).

## What it adds

- A **WhatsApp** sidebar button that opens the native `/whatsapp` workspace tab.
- A WhatsApp chat widget template, currently marked coming soon with no render
  tool.

The app declares no runnables, sidecars, or permission grants of its own.

## Star History

<a href="https://github.com/amajorai/ryu-whatsapp/stargazers">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./.github/shieldcn/star-chart-dark.svg" />
    <img alt="Star history" src="./.github/shieldcn/star-chart-light.svg" />
  </picture>
</a>
