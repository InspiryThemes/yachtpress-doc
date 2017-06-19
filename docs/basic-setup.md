# Basic Setup

## Install Theme
In start, you must have a working version of WordPress already installed. Almost all major web hosts provides one click WordPress install and you can consult your host's help site for more information in this regard. For manual install you can consult WordPress Codex <a target="_blank" href="https://codex.wordpress.org/Installing_WordPress" target="_blank">Installing WordPress</a> especially the <a href="https://wordpress.org/about/requirements/" target="_blank">Requirements</a>.

Once you have a working version of WordPress, You need to download "<a target="_blank" href="../img/basic-setup/all-files.png">All Files and Documentation</a>" from themeforest <a target="_blank" href="https://themeforest.net/downloads" traget="_blank">download page</a> and extract the downloaded zip to get various files including <strong>inspiry-yachtpress.zip</strong>.

### Install Theme Via WordPress Dashboard

<ol>
<li>Go to '<strong>Dashboard</strong> &gt; <strong>Appearance</strong> &gt; <strong>Themes</strong>' section.</li>
<li>Click '<strong>Add New</strong>' and select the '<strong>Upload Theme</strong>' option
    <img src="../img/basic-setup/1.png" alt="">
    <img src="../img/basic-setup/2.png" alt="">
</li>
<li>Choose the <strong>inspiry-yachtpress.zip</strong> file and press '<strong>Install Now</strong>'.
    <img src="../img/basic-setup/3.png" alt="">
</li>
<li>Once the theme is uploaded you need to activate it.
    <img src="../img/basic-setup/4.png" alt="">
</li>
<li>Activating the theme will take you to the themes page. The next step is to <a href="#install-plugins"><strong>Install Plugins</strong></a></li>
</ol>

!!!note ""
     if you face any problem during upload through dashboard, please upload the theme using FTP as guided below.
     
### Install Theme Via FTP ( Alternative Way )

<ol>
<li>Access your hosting server using an ftp client like <a href="https://filezilla-project.org/" target="_blank">FileZilla</a></li>
<li>Go to the '<strong>wp-content/themes</strong>' folder of your WordPress installation</li>
<li>Extract the <strong>inspiry-yachtpress.zip</strong> file and put the inspiry-yachtpress folder in '<strong>wp-content/themes/</strong>' folder.</li>
<li>Go to '<strong>WordPress Dashboard > Appearance > Themes</strong>' section to activate the theme.</li>
</ol>

<div class="section-separator"></div>

## Install Child Theme

It is better to use child theme as if you need to modify anything you modify in child theme only. This way you can easily update your parent theme whenever new update becomes available on themeforest. You can read more about child theme from <a href="https://codex.wordpress.org/Child_Themes" target="_blank">Here</a>.

To install child theme, you need to upload the <strong>inspiry-yachtpress-child.zip</strong> and activate it in the same way as you uploaded and activated the parent theme's <strong>inspiry-yachtpress.zip</strong>.

<div class="section-separator"></div>

## Install Plugins

After you have installed and activated the theme, there'll be a list of <strong>required</strong> and <strong>recommended</strong> plugins at the top of the WordPress dashboard.

<ol>
<li>Click on <strong>Begin Installing Plugins</strong>
    <img src="../img/basic-setup/5.png" alt="">
</li>
<li>Install <strong>required</strong> and <strong>recommended</strong> plugins
    <img src="../img/basic-setup/6.png" alt="">
</li>
<li>Click <strong>Return to Required Plugins Installer</strong> when plugins installation is completed.
    <img src="../img/basic-setup/7.png" alt="">
</li>
<li>Activate the installed plugins.
    <img src="../img/basic-setup/8.png" alt="">
</li>
<li>After activating required plugins, Go to <strong>Easy Boats</strong> plugin settings and save them for 1st time. As guided in screenshot below.
    <img src="../img/basic-setup/9.png" alt="">
</li>
<li>Once all of the above is <strong>Done</strong>. The next step is to <a href="#import-demo-contents"><strong>Import Demo Content</strong></a>.</li>
</ol>

<div class="section-separator"></div>

## Import Demo Contents

To import demo content follow these steps.

<ol>
<li>Go to <strong>Appearance</strong> > <strong>YachtPress Import</strong>.
    <img src="../img/basic-setup/10.png" alt="">
</li>
<li>Click on <strong>Import Demo Data</strong> button.
    <img src="../img/basic-setup/11.png" alt="">
</li>
<li>Wait for importing. It may take couple of minutes to complete.</li>
<li>You can deactivate and delete <strong>One Click Demo Import</strong> plugin when import demo data is completed.
    <img src="../img/basic-setup/12.png" alt="">
</li>
</ol>

<div class="section-separator"></div>

## Configure Permalinks Settings

To configure permalinks settings visit <strong>WordPress Admin > Settings > Permalinks</strong> and configure it as displayed in images below.

<img src="../img/basic-setup/13.png" alt="">