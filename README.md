# NP WordPress Importer

A powerful WordPress plugin for importing pages and posts from Excel files (CSV/XLSX) with support for page hierarchy, Yoast SEO meta, featured images, and more.

## Features

### Excel Import
- Import pages and posts from Excel files (CSV/XLSX)
- Support for page hierarchy through parent-child relationships
- Integration with Yoast SEO for meta titles, descriptions, and focus keywords
- Featured image support
- Custom URL/slug support
- Categories and tags for posts
- Batch processing to prevent timeouts on large imports

### Quick Page Creator
- Create hierarchical page structures quickly
- Paste indented text to create parent-child relationships
- Multiple indentation formats supported:
  - Space/tab indentation
  - Hyphen-based indentation (like markdown)
- Preserves Excel indentation when copying and pasting

### Duplicate Manager
- Find and manage pages/posts with identical titles
- Easily identify and remove duplicates
- Filter by content type

## Installation

### From WordPress.org
1. Go to Plugins > Add New in your WordPress admin
2. Search for "NP WordPress Importer"
3. Click "Install Now" and then "Activate"

### Manual Installation
1. Download the plugin ZIP file
2. Go to Plugins > Add New > Upload Plugin
3. Upload the ZIP file and activate the plugin

## Usage

### Excel Import

1. **Prepare your Excel file** with the following columns:
   - Page Title (required)
   - Page Content (optional)
   - Page URL (optional)
   - Featured Image (optional)
   - Meta Title for Yoast (optional)
   - Meta Description for Yoast (optional)
   - Focus Keyword for Yoast (optional)
   - Parent (optional - for hierarchical structure)

2. **Import your content**:
   - Go to NP Importer in your WordPress admin menu
   - Select the Excel Import tab
   - Upload your CSV or XLSX file
   - Choose content type (Pages or Posts)
   - Click "Start Import"

### Quick Page Creator

1. **Create hierarchical pages** by pasting indented text:
   - Go to the Quick Page Creator tab
   - Paste your hierarchical structure (indented with spaces, tabs, or hyphens)
   - Click "Create Pages"

   Example formats:
   ```
   # Space or Tab Indentation
   About Us
       Our Team
       Our History
   
   # Hyphen-based Indentation
   - About Us
     - Our Team
     - Our History
   ```

### Duplicate Manager

1. **Find and manage duplicates**:
   - Go to the Duplicate Manager tab
   - Click "Find Duplicates"
   - Select which duplicates to remove
   - Click "Delete Selected"

## Template Downloads

The plugin provides template files for both import formats:
- CSV template for Excel Import
- Text templates for Quick Page Creator (space/tab and hyphen formats)

## Compatibility

- WordPress 5.0 or higher
- PHP 7.0 or higher
- Any theme

## Support

For support, feature requests, or bug reports, please visit:
- [GitHub Issues](https://github.com/noblepixels/np-wordpress-importer/issues)
- [Noble Pixels Support](https://www.noblepixels.ca/contact)

## License

This plugin is licensed under the GPL v2 or later.

## About

Developed by [Noble Pixels](https://www.noblepixels.ca), a WordPress development agency focused on creating powerful, user-friendly tools for content management. 