# XPressUI for WordPress

**Stop fighting CSS conflicts. Ship production-ready client intake forms in minutes.**

XPressUI is a decoupled workflow builder and export pipeline for WordPress. Each workflow ships as a standalone package with strictly scoped CSS — locked to a unique root ID — so it renders natively in PHP and remains 100% isolated from your theme. Elementor, Divi, or any other theme literally cannot break the layout.

---

## Why XPressUI

### Theme-Proof by Design
Drop complex, multi-step forms into any WordPress theme and they just work. No `!important` overrides, no late-night CSS debugging, no specificity wars. The workflow package is exported with its own scoped presentation layer.

### Professional Client Intake, Not Just a Form
Upgrade from messy email chains to a structured intake portal that lives inside your client's WordPress site. Guide clients step by step — upload your W-2 here, sign the engagement letter here — and have every submission land in a clean inbox inside `wp-admin`.

### Built for Agency Work
Field IDs are stable across updates. Minor edits (labels, colors, field options) can be done directly from the WordPress admin without re-exporting. Structural changes won't orphan existing submission data.

---

## What's in the Box

This repository distributes the following products:

- **XPressUI WordPress Bridge** (free core plugin) — shortcode renderer, isolated CSS scoping, `wp-admin` submission inbox
- **XPressUI WordPress Bridge Pro** (paid) — Appearance & Design Tokens panel, primary colors, fonts, border radii, all controllable from `wp-admin`
- **Document Intake for WordPress** (paid workflow pack) — production-ready multi-step client onboarding flow with file uploads, ready to install

---

## Install in 3 Steps

### 1. Install the Bridge Plugin (Free)

1. Go to the [Releases page](../../releases/latest).
2. Download `xpressui-wordpress-bridge.zip`.
3. In your WordPress admin, go to **Plugins > Add New > Upload Plugin**, upload the `.zip`, and activate.

### 2. Upload Your Workflow Package

1. Go to **XPressUI > Manage Workflows** in `wp-admin`.
2. Upload the exported `.zip` package — it auto-extracts to `wp-content/uploads/xpressui/`.
3. Copy the generated shortcode (e.g. `[xpressui id="document-intake"]`).
4. Paste it into any page or post and publish.

### 3. Test It

Submit a test entry and confirm the result appears in **XPressUI > Submissions** in `wp-admin`. Uploaded files go directly to your WordPress Media Library.

---

## Bundled Workflows (No Upload Required)

The plugins ship with built-in examples so you can see the decoupling in action immediately:

- **`document-intake`** — multi-step client onboarding flow (bundled with the free core plugin)
- **`validation-playground`** — comprehensive test of all Pro fields (bundled with the Pro plugin)

---

## Pro Plugin: Appearance & Design Tokens

1. Download `xpressui-wordpress-bridge-pro.zip` from the Releases page.
2. Upload and activate it like the core plugin.
3. Go to **XPressUI > Settings** and enter your license key.
4. Open any workflow and click **Customize** to access the Appearance & Design Tokens panel.

---

## Pricing

### WordPress Pack — $129 one-time
- Complete Document Intake multi-step workflow
- XPressUI WordPress Bridge plugin
- Unlimited usage on client sites
- 1 year of updates and email support

### Done For You — $599
- Everything in the WordPress Pack
- We install it on your WordPress site
- We match primary colors to your brand
- We test endpoints and verify email delivery

---

## Support Boundary

Included with purchase:
- Bridge installation and package placement guidance
- Expected endpoint and upload behavior
- `wp-admin` submission screen interpretation

Not included:
- Custom theme or builder integration work
- Custom CPT mapping or webhook chains
- Conflicts caused by third-party plugins outside the bridge contract

---

## Links

- **Buy or learn more:** [iakpress.com/xpressui](https://iakpress.com/xpressui/)
- **Agency integrations & custom work:** [iakpress.com](https://iakpress.com/)
- **Bug reports:** Open an Issue in this repository
