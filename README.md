# Hokus CMS for Platform.sh


Hokus is an open-source CMS for Hugo - completely free to use.

Developers love Hugo because of its astonishing speed.
Content editors love Hokus because it brings the same speed benefit while hiding the complexity of editing raw files to edit a website.
When you save your content, you can see your updated website in your browser almost instantly.

Hokus is a multi-platform desktop application (Windows, macOS, and Linux are supported). Because it runs on your computer, you can use it even when you are offline.
Unlike Netlify, Hokus does not assume any infrastructure vendor, meaning that you are free to move your website to another host without losing the user interface you are used to.




## Services

* Go 1.14

## Post-install

The `content` directory includes two pieces of sample content, provided so that the initial install has some content to show.  Replace it with your actual content as desired.

You can also remove the `minimal` theme if you so desire and replace it with one you download or one you create yourself.

## Customizations

The following changes have been made relative from initializing a new Hugo project with `hugo new site`. If using this project as a reference for your own existing project, replicate the changes below to your project.

* The `.platform.app.yaml`, `.platform/services.yaml`, and `.platform/routes.yaml` files have been added.  These provide Platform.sh-specific configuration and are present in all projects on Platform.sh.  You may customize them as you see fit.
* The `minimal` theme has been included by default.  Feel free to remove it and replace with your own if you prefer.  Consult the Hugo documentation for instructions on how to add and enable themes.

## References

* [Hugo](https://gohugo.io/)
* [Hokus CMS](https://www.hokuscms.com/)
* [Go on Platform.sh](https://docs.platform.sh/languages/go.html)
