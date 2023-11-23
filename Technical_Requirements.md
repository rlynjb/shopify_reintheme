## Technical/Non-Functional? Requirements

Merchants can use **sections** and **blocks** to arrange **page templates**, which provides more flexibility in their store's content, and allows them to control the look and feel of their online store without needing to edit code.

### Template support requirements
- NF1. The system must support the following templates and their format [https://shopify.dev/docs/themes/store/requirements#template-support-requirements]

### Section support requirements
- NF2. All templates must support sections (JSON templates)
- NF3. But we don't need support sections on Customer Account pages, Gift Card pages, and Checkout
- NF4. Templates that support sections should include a setting of type liquid. The Custom Liquid section can act as an insertion point for certain types of apps.
- NF5. Header and footer sections must be rendered within section groups.
- NF6. Section groups allow merchants to dynamically add, remove, and reorder sections in the header and footer areas of the layout.

### Block and app block support requirements
- NF7. Themes must support blocks for all or most elements on the main section of the product page.
- NF8. Ex. Elements such as product price, product vendor, and product description should each be individual blocks within the main product section.
- NF9. Themes must support app blocks (blocks of type @app) in the main product section and featured product section.
- NF10. Introduce Custom Liquid blocks into certain sections.
- NF11. Add a Custom Liquid block anywhere you'd consider adding an app block
- NF12. because the Custom Liquid block can act as an insertion point for certain types of apps. This block should include a setting of type liquid.
- NF13. Implement Best Practices for Sections and Blocks [https://shopify.dev/docs/themes/best-practices/templates-sections-blocks]

  
