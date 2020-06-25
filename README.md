## The Coming Soon GoHugo Theme

Welcome to the universal coming soon theme to your next project.

#### Features
- Multiple templates
- Countdown Timer
- Subscription
- Contact links
- Easy configuration

![Image of examples](/images/grid.png)

### Installation

Inside the folder of your Hugo site run:

```
git submodule add https://github.com/andresmazzo/gohugo-theme-comingsoon.git themes/comingsoon
```

For more information read the official setup guide of Hugo.

### Getting started

After installing the theme successfully it requires a just a few more steps to get your site running.

**The config file**

Take a look inside the exampleSite/ folder. See `config.toml` file. To use it, copy it in the root folder of your Hugo site. Feel free to change the strings in this theme.
You may need to delete the line: themesDir = "../.."

### Templates

- simple
- split-view
- minimal-left

See [screenshot pics](/docs/pics)!

### Custom CSS

So, you define the template, but you would like to adjust some things. Don't worry. You can override the built-in css by using your own. 
Create your own files in `/static` dir of your website and edit config file. 

Example: Your css files are in `static/css/`:

```
[params]
  custom_css = ["css/overrides.css"]
```

### Social links
Set your social contact links. We implement [simple icons](https://simpleicons.org)
```
[params]
  ..

  [[params.socials]]
  icon = "facebook"
  url = "https://facebook.com/fakeuser"
  [[params.socials]]
  icon = "instagram"
  url = "https://instagram.com/fakeuser"
```


### Subscription
Do you know formspree.io? We support it to send the email of the subscription form. Visit the Formspree site to get the "action" link and add it to your config file.
```
[params]
  subscription_action = "https://formspree.io/asdfgher"
```

### Development

See [docs dir](/docs) for more info.

### Contributing

If you find a bug or have an idea for a feature, feel free to use the [issue tracker](/https://github.com/andresmazzo/gohugo-theme-comingsoon) to let me know.