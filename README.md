# <p align=center>aram-ghamoyan/magento2-bottomdescription</p>

<div align="center">
  <p align=center>Bottom Description for Magento 2</p>
  <img src="https://img.shields.io/badge/magento-~2.3-orange.svg" alt="Supported Magento Versions" />
  <img src="https://img.shields.io/badge/maintained-yes-brightgreen.svg" alt="Maintaind" />
  <img src="https://img.shields.io/badge/license-GPL--3.0-blue.svg" alt="License" />
</div>

**Features**

- Adds a "Bottom Description" field to category edit pages in the admin panel
- Displays the bottom description content below product listings on category pages
- Fully integrated with Magento's category management system
- WYSIWYG editor support for rich content formatting
- SEO-friendly content placement

**Requirements**

- Magento 2.3.x or higher
- PHP 7.2 or higher

**Installation**

*Via Composer (Recommended)*
```bash
composer require aram-ghamoyan/magento2-bottomdescription
php bin/magento module:enable AramGhamoyan_BottomDescription
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento cache:clean
```

*Manual Installation*

1. Download the module files
2. Create the directory structure: app/code/AramGhamoyan/BottomDescription
3. Copy the module files to this directory
4. Run the following commands:
```bash
php bin/magento module:enable AramGhamoyan_BottomDescription
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento cache:clean
```

**Usage**

1. Navigate to Catalog > Categories in your Magento admin panel
2. Select the category you want to edit
3. Find the "Bottom Description" field in the category information section
4. Add your content using the WYSIWYG editor
5. Save the category
6. The bottom description will now appear below the product listings on the category page

**Use Cases**

The bottom description is perfect for:

- **SEO Content**: Add keyword-rich content below product listings to improve search engine rankings
- **Additional Information**: Provide buying guides, category information, or helpful tips
- **Marketing Content**: Promote special offers, features, or benefits related to the category
- **User Guidance**: Help customers make informed decisions with detailed category descriptions
- **Brand Storytelling**: Share your brand story or category-specific narratives

**Configuration**

The module works out-of-the-box with no additional configuration required. The bottom description field is automatically added to all category pages.

**Customization**

To customize the appearance of the bottom description, you can override the template files in your theme or use custom CSS to style the content.

**License**

This project is licensed under the GNU General Public License v3.0

**Support**

For issues, questions, or contributions, please visit the GitHub repository at github.com/aram-ghamoyan/magento2-bottomdescription

**Contributing**

Contributions are welcome! Please feel free to submit a Pull Request.

**Author**

Aram Ghamoyan
