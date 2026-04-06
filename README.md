# XPressUI Bridge — Beta Tester Guide 🚀

Welcome to the XPressUI private beta! 

If you are here, you know the struggle of dropping a complex, multi-step form (like Gravity Forms or WPForms) into a heavy WordPress theme like Elementor or Divi, only to spend hours fighting CSS specificity wars and global input resets.

XPressUI is a decoupled form builder. The form ships as a standalone artifact with its own **strictly scoped CSS** (locked to a unique root ID). It renders natively in PHP and is **100% theme-proof**. The theme literally cannot break the layout, but you can still tweak design tokens natively in the wp-admin.

Here is how to install the plugins and test the workflow.

---

## 📦 1. Install the Core Plugin (Free)

The core plugin provides the engine: the shortcode renderer, the isolated CSS scoping, and the wp-admin submission inbox.

1. Go to the [Releases page](../../releases/latest) of this repository.
2. Download `xpressui-bridge-1.0.39.zip`.
3. In your WordPress admin, go to **Plugins > Add New > Upload Plugin**.
4. Upload the `.zip` file and click **Activate**.

---

## 💎 2. Install the Pro Plugin (Design Tokens & Overrides)

The Pro version unlocks the **Appearance & Design Tokens** panel, allowing you to natively tweak primary colors, fonts, and border radii without writing any CSS.

1. Go to the Releases page and download `xpressui-wordpress-bridge-pro-1.0.30.zip`.
2. Upload and activate it exactly like the core plugin.
3. Go to **XPressUI > Settings** in your WordPress admin.
4. Enter the **Lifetime Agency License Key** you received in your private message.

---

## 🚀 3. Import and Test a Workflow

To see the decoupling in action:

1. Go to **XPressUI > Workflows** in your WordPress admin.
2. Click **Upload Package** and upload a `.zip` workflow exported from the XPressUI Console (or use the sample package provided in the releases).
3. Copy the generated shortcode (e.g., `[xpressui id="document-intake"]`) and paste it into any page or post.
4. Check the page on the frontend: notice how it ignores your theme's global CSS resets.
5. Go back to wp-admin, click the **Customize (PRO)** button on your workflow.
6. Open the **Appearance & Design Tokens** tab, change the Primary Color and the Font Family, save, and refresh your frontend!

---

## 💬 Feedback & Bug Reports

As a beta tester, your brutal feedback is our most valuable asset. 

If you find a bug, a CSS bleed from a specific theme, or a confusing UI flow:
- Open an Issue in this repository.
- Or reply directly to the DM where you received your license key.

Thank you for helping us make WordPress forms theme-proof!