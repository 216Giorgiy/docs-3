# Footer

**Techmarket**'s footer has 3 rows with 2 widget areas separated by a **Footer Newsletter Section**.

* The 2 widget areas are **Footer Widgets** and **Footer Bottom Widgets**.  You can drag and drop your widgets from Appearances > Widgets. However **if there were no widgets present in this areas, it would load the default widgets**.

* The last row of the footer is called **Copyright Bar** which has **Copyright Information** on left and **payment logo** on right.

Here is the Footer's anatomy:

![](http://transvelo.github.io/docs/electro/images/footer-anatomy.png)

## First Row of Footer

The **Newsletter Block and Social Media** is the top most row in the footer.

### **Configuring Newsletter Form**-

Display Newsletter Sign-up Form to know about new Products.
1. Navigate to **Contact > Contact Forms**.
2. In the form markup textarea, edit the existing code as follows :<br/><br/>

    ```

    <div class="form-group row">
<div class="col-xs-12 col-md-6">
<label>First name <abbr class="required" title="required">*</abbr></label>
    [text* first-name class:input-text  first-name]
</div>
<div class="col-xs-12 col-md-6">
<label>Last name <abbr class="required" title="required">*</abbr></label>
    [text* last-name class:input-text  last-name]
</div>
</div>

<div class="form-group">
<label>Subject</label>
    [text subject class:input-text your-subject]
</div>

<div class="form-group">
<label>Your Message</label>
    [textarea your-message]
</div>

<div class="form-group clearfix">
<p>[submit "Send Message"]</p>
</div>

    ```


3. Click on **Save** button and view the output.


Here is the contact-form setting

![](../images/footer-newletter-form.png)

### **Social Icons**

**Social Icons** - Links to Social media profiles. It can be set from **Techmarket > Social Media Media**<br/>![](../images/theme-options-social-media.png)




In the preview it has 3 widgets. Technically it is possible to have more than or less than 3 widgets and the width will be automatically adjust to be equally shared by the number of widgets.

By default the footer widget area is populated with 3 instances of 2 widgets and they are :

1. **WooCommerce Products** Widget - configured to display **Featured Products**
2. **WooCommerce Products** Widget - configured to display **On Sale Products**
3. **WooCommerce Top Rated Products** Widget.

![](http://transvelo.github.io/docs/electro/images/footer-widget-area.png)

## Footer Contact Information

The **Footer Contact Information** is just below the **Footer widgets** and is separated by **Footer Newsletter Form**. This section has :

* **Logo** - Footer Logo can be set from **Electro > Footer > Footer Contact Block > Your Logo**.
* **Footer Contact Text** - The default value is *"Got Questions ? Call us 24/7!"* and can be changed from **Electro > Footer > Footer Contact Block > Call us text**.
* **Footer Contact Number** - The default value is *"(800) 8001-8588, (0600) 874 548"* and can be changed from **Electro > Footer > Footer Contact Block > Call us number**.
* **Footer Contact Info Address** - The default value is "*17 Princess Road, London, Greater London NW1 8JR, UK 1-888-8MEDIA (1-888-892-9953)*" and can be changed from **Electro > Footer > Footer Contact Block > Footer Address**.
* **Footer Social Icons** - Links to Social media profiles. It can be set from **Electro > Footer > Footer Contact Block > Show Footer Social Icons**<br/>![](http://transvelo.github.io/docs/electro/images/theme-options-social-media.png)
* Edit the information as required and click on **Save Changes** in **Electro** page.

## Footer Bottom Widget Area

The **Footer Bottom Widget Area** is adjacent to **Footer Contact Information** section. It is a widgetized area and it can contain any number of widgets. It can be populated from **Appearance > Widgets > Footer Bottom Widget Area**.

In the preview it has 3 widgets. Technically it is possible to have more than or less than 3 widgets.

By default the footer bottom widget area is populated with 3 instances of 3 widgets and they are :

1. **WooCommerce Categories** Widgets - configured to display **Find It Fast** section
2. **WP Meta** Widget - configured to display **Meta** Information links.
3. **WP Pages** Widget - configured to display **Pages** menu links.

<div class="alert alert-warning alert-block">
**Pro Tip:** Each widget in **footer bottom widget area** has a margin-left of **5.357em** ( CSS Rule : **.footer-bottom-widgets .columns + .columns**). Adjust the margin-left value to accomodate more widgets.
</div>

![](http://transvelo.github.io/docs/electro/images/footer-bottom-widgets.png)

## Copyright Bar

The **Copyright Bar** can be configured via **Electro > Footer > Footer Credit Block**.

1. **Footer Credit** - the default is "*&copy; &lt;a href="&lt;website-url&gt;"&gt;electro&lt;/a&gt; - All Rights Reserved.*"
2. **Payment Logos** - Displays all the payment methods available to the user. There is no default and each logo needs to be uploaded to media library. The recommended resolution for payment logos is **40x29 pixels**

![](http://transvelo.github.io/docs/electro/images/theme-options-copyright-bar.png)
