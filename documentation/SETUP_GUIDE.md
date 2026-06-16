# TrustBuyShop - Shopify Store Setup Guide

## Overview
This guide walks you through setting up your Shopify store for the 25 in 1 Mini Screwdriver Set.

## Prerequisites
- Shopify account (free trial or paid plan)
- Basic understanding of Shopify admin
- Product images (recommended: 3-5 high-quality product photos)
- Bank account for payment processing

## Step 1: Create Shopify Store

1. Go to [shopify.com](https://shopify.com)
2. Click "Start free trial"
3. Enter your email and create a password
4. Fill in store details:
   - Store name: **TrustBuyShop**
   - Store address: Your location
5. Complete the setup wizard

## Step 2: Configure Basic Settings

### Store Name & Domain
- **Settings → General**
  - Store name: TrustBuyShop
  - Store email: support@trustbuyshop.com (or your preferred email)

### Currency & Location
- **Settings → General → Plan and permissions**
  - Currency: USD
  - Time zone: Your timezone

## Step 3: Add Product

### Create Product
1. Go to **Products → All Products**
2. Click **Add product**
3. Fill in product details:

**Product Name:** 25 in 1 Mini Screwdriver Set

**Description:**
```
Professional-grade 25-in-1 mini screwdriver set featuring precision flat head and cross-shaped screwdrivers. Perfect for smartphone repair, laptop maintenance, camera servicing, and other electronics.

Includes:
• 25 precision-engineered bits
• Magnetic screwdriver handle
• Non-slip ergonomic grip
• Chrome vanadium steel bits
• Compact portable carrying case
• 12-month warranty

Ideal for:
✓ Electronics repair professionals
✓ DIY enthusiasts
✓ Gadget owners
✓ Maintenance specialists
```

### Add Pricing
- **Pricing**
  - Price: $25.00
  - Cost per item: (Your cost - optional but recommended)
  - Tax class: Standard

### Add Inventory
- **Inventory**
  - SKU: MINI-SCREW-25-FB
  - Barcode: TBS-2501-FB
  - Track quantity: Yes
  - Quantity: 100 (or your stock level)

### Add Images
1. Click **Add media**
2. Upload product images:
   - Main product image
   - Detail shots showing bits
   - Carrying case image
   - In-use demonstration

### Add Variants (Optional)
If offering color options:
1. Click **Add options**
2. Option name: Color
3. Variant values: Black, Silver, Blue
4. Set different prices if needed

## Step 4: Configure Collections

### Create Collection
1. Go to **Products → Collections**
2. Click **Create collection**
3. Name: Featured Products
4. Add your product
5. Set collection image

## Step 5: Customize Theme

### Choose Theme
1. Go to **Online Store → Themes**
2. Choose a mobile-responsive theme (e.g., Dawn)
3. Click **Customize**

### Customize Product Page
1. In theme editor, navigate to **Product page template**
2. Update the template with `shopify-theme/product-page.liquid`
3. Ensure the following elements are included:
   - High-quality product images
   - Product title and price
   - Key features list
   - Add to cart button
   - Trust badges
   - Customer reviews section

### Homepage Customization
1. Go to **Online Store → Pages**
2. Click **Home**
3. Add sections:
   - Hero banner with product image
   - Product featured section
   - Benefits/Features section
   - Customer testimonials
   - CTA to product page

## Step 6: Set Up Payment Methods

### Configure Payments
1. Go to **Settings → Payment providers**
2. Set primary payment provider:
   - Shopify Payments (recommended) OR
   - Other payment gateways (Stripe, Square, etc.)
3. Enter bank account details

### Supported Payment Methods
Enable:
- Credit cards (Visa, Mastercard, American Express)
- PayPal
- Apple Pay
- Google Pay

## Step 7: Configure Shipping

### Shipping Zones
1. Go to **Settings → Shipping and delivery**
2. Click **Add shipping zone**
3. Create zones:

**Zone 1: United States**
- Countries: United States
- Shipping rate: $5.99 (or flat rate)
- Free shipping over $50

**Zone 2: International (if applicable)**
- Countries: Select regions
- Shipping rate: $15.99

## Step 8: Set Up Email Notifications

### Transactional Emails
1. Go to **Settings → Notifications**
2. Enable emails:
   - Order confirmation
   - Shipping confirmation
   - Order cancellation
   - Order refund

Use `marketing/email-template.html` as reference for styling

## Step 9: Configure SEO

### Basic SEO
1. Go to **Online Store → Pages**
2. For each page, click **Edit website SEO**
3. Set:

**Product Page SEO:**
- Title: 25 in 1 Mini Screwdriver Set | TrustBuyShop
- Meta description: Professional-grade 25-in-1 mini screwdriver set with flat head and cross-shaped bits. Perfect for electronics repair.
- URL: `/products/mini-screwdriver-set`

### Add Keywords
Focus on:
- mini screwdriver set
- precision screwdrivers
- electronics repair tools
- phone repair kit
- laptop repair tools

## Step 10: Set Up Analytics

### Google Analytics
1. Go to **Settings → Apps and integrations**
2. Search for "Google Analytics"
3. Install and configure
4. Add tracking ID from `shopify-theme/store-settings.json`

### Facebook Pixel
1. Go to **Settings → Apps and integrations**
2. Search for "Facebook"
3. Install Facebook Sales Channel
4. Connect to your Facebook business account

## Step 11: Add Trust Elements

### Add Reviews App
1. Go to **Apps → App Store**
2. Search for review app (e.g., Trustpilot, Yotpo)
3. Install and configure

### Policy Pages
1. Go to **Online Store → Policies**
2. Create/update:
   - Privacy Policy
   - Return Policy
   - Shipping Policy
   - Terms of Service

## Step 12: Test Checkout

### Complete Test Purchase
1. Add product to cart
2. Proceed to checkout
3. Enter test payment info (varies by provider)
4. Verify:
   - Payment processes correctly
   - Confirmation email sends
   - Order appears in admin

## Step 13: Launch Store

### Pre-Launch Checklist
- [ ] Product details complete and accurate
- [ ] High-quality product images uploaded
- [ ] Pricing correct
- [ ] Shipping configured
- [ ] Payment methods enabled
- [ ] Theme customized
- [ ] Policy pages created
- [ ] Analytics set up
- [ ] Test purchase completed
- [ ] Trust badges/reviews configured

### Remove Password Protection
1. Go to **Online Store → Preferences**
2. Uncheck "Password protect your online store"
3. Click **Save**

### Enable Domain
1. Go to **Settings → Domains**
2. Add custom domain (optional)
3. Configure DNS records

## Step 14: Marketing Setup

### Email Marketing
1. Install email marketing app:
   - Klaviyo
   - Mailchimp
   - Omnisend
2. Create email campaigns:
   - Welcome series (3-5 emails)
   - Abandoned cart recovery
   - Post-purchase follow-up

### Social Media
1. Add social media icons in footer
2. Create accounts on:
   - Facebook
   - Instagram
   - TikTok
   - LinkedIn

### Paid Advertising
1. Set up advertising accounts:
   - Facebook/Instagram Ads
   - Google Shopping
   - TikTok Ads
2. Create campaigns targeting:
   - Electronics enthusiasts
   - DIY repair communities
   - Tech-savvy consumers

## Ongoing Maintenance

### Regular Tasks
- Monitor inventory levels
- Respond to customer inquiries
- Review and respond to product reviews
- Update blog with tips and tricks
- Analyze sales data and adjust strategy
- Monitor website performance

### Monthly
- Review sales metrics
- Check inventory stock
- Update marketing campaigns
- Analyze customer feedback

### Quarterly
- Review and optimize product page
- Update pricing if needed
- Analyze competitor activity
- Plan seasonal promotions

## Troubleshooting

### Common Issues

**Product not showing on store:**
- Verify product status is "Active"
- Check inventory quantity > 0
- Ensure theme is properly installed

**Payment not processing:**
- Verify payment provider is activated
- Check payment method settings
- Test with different payment method

**Emails not sending:**
- Verify notification settings
- Check email provider configuration
- Test with test order

## Resources

- [Shopify Help Center](https://help.shopify.com)
- [Shopify Community Forums](https://community.shopify.com)
- [Shopify API Documentation](https://shopify.dev)

## Support

For questions or issues:
- Email: support@trustbuyshop.com
- Shopify Support: help.shopify.com
