# Translating Alt Text Hall of Fame

[Alt Text Hall of Fame](https://alttexthalloffame.org/) is a fairly simple, one-page [WordPress](https://wordpress.org/) site. It uses the [Twenty Twenty-Three WordPress theme](https://wordpress.org/themes/twentytwentythree/), the [Fediverse Embeds](https://wordpress.org/plugins/fediverse-embeds/) plugin to embed Mastodon posts, and the [Polylang](https://wordpress.org/plugins/polylang/) plugin to manage translations.

## Translation workflow

## Site admin

1. [Add new language.](https://alttexthalloffame.org/wp-admin/admin.php?page=mlang)
2. [Add new translation](https://alttexthalloffame.org/wp-admin/post.php?post=2&action=edit) (see sidebar under "Languages"), save the new page as a draft.
3. Copy the content of the original home page into the new draft page.
4. Create a new account for the translator.
5. Assign the draft translation page to the translator.

## Translator

After logging in, you can [view translations that have been assigned to you](https://alttexthalloffame.org/wp-admin/edit.php?post_type=page).

A few things to keep in mind.

1. You don't have to translate everything to the word. Be natural, use common expressions and cultural references from your language. 
2. Keep things simple, positive, and respectful. The goal is to show the positive side of describing images we share online and encourage doing this.
3. If English is a common language in your country, you don't have the translate the first few embedded posts (excluding the alt text examples in the "But how do I know what to write?" section). There is currently no mechanism in place to translate these, so if you need to do so, please replace the iframe HTML code with a translated quote and link to the original fediverse post. For the example alt text, you can keep the embed code and only translate the alt text next to it.

Also, be sure to [edit your profile](https://alttexthalloffame.org/wp-admin/profile.php) so that you can be [properly credited for your work](https://alttexthalloffame.org/en/#contributors); specifically your display name and a URL of your website or social media profile. (Your email will not be publicly displayed.)
