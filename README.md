## The Coming Soon GoHugo Theme

Welcome to the universal coming soon theme to your next project.

#### Features
- Flexible
- Multiple templates
- Countdown Timer
- Subscription

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

### Custom CSS

So, you define the template, but you would like to adjust some things. Don't worry. You can override the built-in css by using your own. 
Create your own files in `/static` dir of your website and edit config file. 

Example: Your css files are in `static/css/`:

    [params]
      custom_css = ["css/overrides.css"]

### Development

See [docs dir](/docs) for more info.

### Contributing

If you find a bug or have an idea for a feature, feel free to use the [issue tracker](/https://github.com/andresmazzo/gohugo-theme-comingsoon) to let me know.