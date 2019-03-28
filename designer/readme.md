

# Getting Started




## 1 Activate your License
It’s strongly recommended that you add your theme’s license key from within the License section of the WordPress Customizer. By adding your key, you will activate the remote theme updates and have access to our support team.

You can find your theme’s license key by checking your purchase receipt or signing in to your ThemeBeans dashboard.

If you purchased the theme from ThemeForest, you may [request your license key here][1]. You’ll need your ThemeForest purchase code handy.

Copy this key and navigate to the **Customizer License Control** located within the **WordPress Dashboard > Customizer > Theme License** section.

Enter your license key and hit activate.

You'll see a "Verified" report upon a successful activation. If the license does not activate, please refresh and try again.

![license](https://user-images.githubusercontent.com/1813435/35998646-4876974a-0ceb-11e8-8b20-78decf11c1d1.jpg)


## 2. Install the Child Theme
If you plan on modifying anything within the theme files directly, please install the included child theme. If you change anything within the theme folder and approve an update from our servers **your modifications will be lost**. By using a child theme you will ensure that your changes are preserved.

Log in to your website's dashboard and navigate to the Dashboard \> Appearance \> Themes page. Click **Add New** and follow the directions to upload the designer-child.zip file, located in your theme’s package download.

Simply click **Activate** and both the Designer theme and Designer child theme will be active on your WordPress site. Now have at it.

## 3. Install Recommended Plugins
Please install the recommended WordPress plugins through the notice at the top or your admin dashboard. Once clicked, you will be taken to the **Plugin Installation** admin view, where you may install and activate each plugin, as depicted here:

## 4. Install Demo Data
When you first activate Designer, it will look like a simple website with your existing content. This is expected since Designer needs you to modify a few settings before it will look exactly like the demo.

Optionally, you may install our Designer demo data, which will populate your site with the pages you see on our live demo. This can give you a head start in setting up your site. Once you get your site setup and get the hang of it, you may delete the unwanted posts or pages as you see fit.

You can find the designer.xml data file in the theme package download. You can install this XML file by going to **Tools** → **Import** → **WordPress** and click **Choose File**. Upload the XML file and follow the steps to import. Please note that you should have all required custom post type plugins installed before importing the data - otherwise, you’ll need to re-import the .xml file.

When the demo data is finished importing, you should have several new posts and pages to work with going forward.

## 5. Prepare your Images
In order to get the best looking images in Designer, we need to refresh your images to be cropped to Designer’s image sizes. We do this with the [Regenerate Thumbnails][2] plugin.

After activating the plugin, go to **Tools** → **Regen. Thumbnails**, then press the **Regenerate All Thumbnails** button to start generating new image sizes.

Once it’s finished, your library of images will be optimized and ready to go.




# Set up your Home Page

## 1. Create a New Page
First, create a new page on your website, with the **WP Dashboard** \> **Pages** \> **Add New** link. Then assign the Portfolio template to your new page, as pictured below.

Note that in newer versions of Designer, there’s no need to set the Portfolio Template, as the home page will take on the characteristics of the portfolio template.

![][image-1]

## 2. Navigate to the Customizer
Next, you will need to set the page as your site's front page, via the **WP Dashboard** \> **Appearance** \> **Customize** page, within the Static Front Page panel. 

![][image-2]

## 3. Set a Static Page

Next, to establish a static page, open the **Static Front Page** panel, within the Customizer.

![][image-3]

## 4. Assign a Front Page

From the “Static Front Page” panel, select the static page option. This will set your website to display a page, instead of a blogroll, on the home page. 

Next select the templated page you first created as the Front Page option. 

Then hit the **Save & Publish** button up at the top of the Customizer window, and you should be all set.

![][image-4]




# Assign Menus
To set your menus, locate the Menu options by selecting the “Appearance” tab from the dashboard sidebar and then “Menus”.

Once you’re viewing the Menus, create a new menu and save it. After you’ve saved the menu, you can add it to a menu via the Menu Settings, below the Menu Structure area. Add your pages and links to the menu you just created in the Menu Structure area.


## Footer Menu
Add a footer menu to your webite simply by creating a menu and assigning it to the Footer Menu location - as described above.

## Social Menu
The icons added to your Social Menu will automatically populate. To add the icons, create a custom link to the social media location and Designer will do the rest.

To also display the social menu in the site flyout, select the Navigation Social Icons checkbox within the **Customizer** \> **Theme Options** \> **Flyout** section.




# Template Settings

## Page Featured Images
Designer includes support for page featured images. You can add featured images via the Featured Image meta module, located below the Publish and Page Attributes metaboxes, on the right side of your page editor.

## Template Settings
On each page you'll see a Template Settings metabox, located below the page content editor. This metabox includes the options to display the page title, enable the parallax animations, insert a header tagline and to select the page layout (_Content Left, Content Right & Fullwidth_).

![][image-5]

## Tagline Animation
We've added in a neat animated typing effect that can be used in the header tagline textarea. [Here is an example][3] of the animation code deployed throughout the demo.

Add this to the Header Tagline textarea within the "**Template Settings**" metabox (_located beneath the page editor_), and swap out the text, add more \<b\> elements and such.

Note: You can work the code however preferred, as long as you have the correct \<span\> wrap, with \<b\> elements within it.


## The Contact Template
To set up the Contact Template, simply create a page using the "Contact" template and publish it. Within the Customizer you'll find a **Contact** section, which includes settings for the optional Google Map section and optional page links added to the content.

To add contact links to the Contact template, head to the **Customizer** \> **Theme Options** \> **Contact** section and select the pages you'd like to link to.

![][image-10]




# Build your Portfolio

## 1. Portfolio Plugin
To install the Bean Portfolio plugin, head over to our website and [download the plugin][4]. This theme also works well with the Portfolio Post Type plugin. As long as one of those plugins are installed, you’re good to go.

Once you’ve successfully downloaded the zip file, head to your WordPress Dashboard and select **Plugins** \> **Add New** \> **Upload**. Add the zipped file in the field there and click Upload.

Upon a successful upload, you’ll be prompted to activate the plugin. You’ll then see a new “Portfolio” tab in your WordPress Dashboard sidebar. Creating portfolio posts is done exactly the same as standard posts.

## 2. Thumbnails

Upload a featured image - any size will work. The images will be automatically applied throughout all the neccessary templates and loops.

## 3. Gallery Images

This is where you will add your images to the post by clicking the "Browse & Upload" button. You have the capability to rearrange, caption, add more and remove images from the popup modal that appears.

Just remember to hit Save Gallery and you're all set.

![][image-6]

## 4. Formats

Designer is capable of outputting gallery and video portfolio posts (embedded - e.g. Vimeo & YouTube). To change the type of portfolio to display, click on the checkboxes under the "**Portfolio Format**" metabox, located beneath the Portfolio Categories, on the right hand side of your window.

![][image-7]

## 5. Meta

Each portfolio post has selectable meta options that you may choose to use on each individual post. You can set the date, client, role, url, elect to display the categories, tags, views and the portfolio post title.

You can also add an external URL to which your post loop will link to a different URL than it's single post page. For example, you can create a post with a featured image and an external link to your Behance project page - then promote that project within the portfolio templates.

![][image-8]

## 6. Options

Located within the Theme Customizer you will find a Portfolio section. Here you may elect to enable the singular portfolio loop, portfolio sorting, lazy-loading, photoswipe and enter your portfolio count.

## 7. Call to Action

In the Customizer you’ll find the single portfolio Call to Action settings. You can enable a call to action button that outputs a project query form upon clicking it.

![][image-9]




# Frequently Asked

1. **How do I update my theme?** With an active license key, you’ll receive a notification in the WordPress Dashboard whenever there is an update available. You can then update right in your WordPress dashboard, keeping your site healthy and secure.

2. **How do I get help?** You can request support via our official [Help Center][5]. We’re here to help with any technical questions, though any customization requests should be directed [here][6].

3. **Do I need a theme license key?** You don’t need a key to use the theme, but in order to receive support and in-dashboard update notifications, an active license key is required.

4. **How do I get a license key** You can find your theme’s license key by checking your ThemeBeans purchase receipt or signing in to your ThemeBeans dashboard. If you purchased the theme from ThemeForest, you may [request your license key here][7].

5. **How long is my license key valid for?** Initial licenses are issued on an annual basis. If you’ve purchased from ThemeForest, you’ll have access to support and in-dashboard updates as long as you have a support package.

6. **Can I use my theme with an expired license** You sure can! You just won’t have access to in-dashboard updates, as well as our support team.




# Need Help?
Have questions? [Get in touch][8] with a friendly member of our team and we’ll be happy to help.

## Support Tips

**Troubleshoot first.** The best way to troubleshoot plugin conflicts is by deactivating all WordPress plugins and activate them one by one. Also, don’t forget to empty your cache if you are using a caching plugin.

**Use the Help Center.** Please use our official Help Center to ask for help. It’s monitored daily and the only designated support channel.

**Please be nice.** You should always be nice to the support personal. The folks on our support team really do enjoy helping others, but you can really ruin their day by using negative words.

[1]:	https://themebeans.com/themeforest "Request a License Key"
[2]:	https://wordpress.org/plugins/regenerate-thumbnails/ "Regenerate Thumbnails WordPress Plugin"
[3]:	https://gist.github.com/richtabor/f95171410f2d0f575ede891830ffea54 "Example gist of Designer's animated typography"
[4]:	https://themebeans.com/plugins/bean-portfolio
[5]:	https://themebeans.com/contact
[6]:	https://themebeans.com/customizations
[7]:	https://themebeans.com/themeforest
[8]:	https://themebeans.com/contact

[image-1]:	https://d33v4339jhl8k0.cloudfront.net/docs/assets/5744b893c697917290ddc31b/images/595ff0262c7d3a707d7b83df/file-Uwb9DvvQyK.jpg "Create a New Page"
[image-2]:	https://d33v4339jhl8k0.cloudfront.net/docs/assets/5744b893c697917290ddc31b/images/595fecf50428637ff8d462b8/file-6DaAqO3m5Y.jpg "Open the Static Front Page panel, in the Customizer"
[image-3]:	https://d33v4339jhl8k0.cloudfront.net/docs/assets/5744b893c697917290ddc31b/images/595fed1c0428637ff8d462bb/file-pyUecy41SC.jpg "Set a Static Page"
[image-4]:	https://d33v4339jhl8k0.cloudfront.net/docs/assets/5744b893c697917290ddc31b/images/595fee092c7d3a707d7b83c1/file-kPOj2r5Dq3.jpg "Assign a new Front Page"
[image-5]:	https://user-images.githubusercontent.com/1813435/35998432-9345786e-0cea-11e8-9e9b-d7f172ad5ef8.jpg
[image-6]:	https://user-images.githubusercontent.com/1813435/35998452-a36321b0-0cea-11e8-8b24-d59227af73ff.jpg
[image-7]:	https://user-images.githubusercontent.com/1813435/35998453-a37ae5de-0cea-11e8-8a81-a07226b26184.jpg
[image-8]:	https://user-images.githubusercontent.com/1813435/35998452-a36321b0-0cea-11e8-8b24-d59227af73ff.jpg
[image-9]:	https://user-images.githubusercontent.com/1813435/35998451-a34eac80-0cea-11e8-98a1-110d3a5990f1.jpg
[image-10]:	https://user-images.githubusercontent.com/1813435/35998450-a3407336-0cea-11e8-80ab-e3c6121b610b.jpg