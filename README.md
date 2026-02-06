**This Plugin has to be released publically yet.**
# Zulkaif SEO File Manager

A manual SEO file manager for WordPress. Generate and control sitemaps, robots.txt, ads.txt, and other essential SEO files with full transparency and no silent automation.

## Description

**SEO File Manager** is a lightweight, manual-control WordPress SEO utility plugin designed to help site owners **generate, preview, and manage essential SEO-related files** without automation side effects.

The plugin focuses on **transparency, user control, and WordPress-native behavior**, avoiding silent overrides and respecting existing plugins, files, and configurations.

### Key Features

- **Manual Sitemap Generation**: Create XML sitemaps with full control over what's included
- **Robots.txt Management**: Safely edit and preview robots.txt rules
- **Ads.txt Editor**: Manage advertising declarations with entry-based or raw editing
- **Conflict Detection**: Alerts you to potential conflicts with other SEO plugins
- **No Silent Automation**: All actions require explicit user approval
- **WordPress Native**: Uses WordPress APIs and follows coding standards

## Installation

1. Upload the `basicseo` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Navigate to **Zulkaif Seo** in your WordPress admin menu
4. Configure your settings and generate your sitemap

## Features in Detail

### Sitemaps

- Choose which content types to include (posts, pages, media, categories, tags)
- Manual generation - you control when the sitemap updates
- Exclude noindex content automatically
- Preview before making live
- Compatible with WordPress core sitemaps

### Robots.txt

- Add custom rules safely without overriding WordPress core
- Live preview of effective robots.txt
- Automatic sitemap reference
- Physical file detection warnings
- Multiple sitemap source options

### Ads.txt

- Entry-based management with validation
- Raw text editor for advanced users
- Physical file creation with WP Filesystem API
- Virtual fallback if directory not writable
- Prevents incorrect entries with clear warnings

### Advanced Settings

- Cache duration control
- Physical file preference
- Conflict detection toggle
- Debug mode for troubleshooting
- System information display

## Usage

### Generate a Sitemap

1. Go to **Zulkaif SEO > Sitemaps**
2. Configure which content types to include
3. Click **Generate Sitemap**
4. Submit your sitemap URL to search engines

### Edit Robots.txt

1. Go to **Zulkaif SEO > Robots.txt**
2. Add your custom rules in the editor
3. Configure sitemap reference
4. Preview before saving

### Manage Ads.txt

1. Go to **Zulkaif SEO > Ads.txt**
2. Add entries provided by your ad networks
3. Choose between entry manager or raw editor
4. Save settings

## Requirements

- WordPress 6.0 or higher
- PHP 7.4 or higher

## Support

For support, please contact:
- Email: mail@zulkaif.com
- Website: https://zulkaif.com/
- Plugin URI: https://zulkaif.com/seo-file-manager.html

## Author

**Zulkaif Riaz**
- Website: https://zulkaif.com/
- Email: mail@zulkaif.com

## License

This plugin is licensed under the GPL v3 or later.

## Changelog

### 1.0.0
- Initial release
- Sitemap generation
- Robots.txt management
- Ads.txt editor
- Conflict detection
- WordPress 6.9 tested

## Credits

Created by Zulkaif Riaz with a focus on transparency, user control, and WordPress best practices.

---

**Note**: This plugin does not automatically update sitemaps or make changes without user action. It's designed for users who want full control over their SEO files.
