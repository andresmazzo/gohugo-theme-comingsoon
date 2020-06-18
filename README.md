## The Coming Soon GoHugo Theme

This theme acts like a flexible coming soon theme to your next project.

#### Features
- Flexible
- Multiple templates
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

Take a look inside the examples/ folder of this theme. You'll find multiple site examples. Select one and see file called config.toml. To use it, copy the config.toml in the root folder of your Hugo site. Feel free to change the strings in this theme.

You may need to delete the line: themesDir = "../.."

### Development

**Update git submodule**
```
git submodule update --recursive --remote
```

**Create template from scratch**
Create html dir:
```
cd layouts/partials/templates
mkdir your-template-name
cd your-template-name
vim index.html
```

Create css file:
```
cd static/css/templates
vim your-template-name.css
```

**Create template based on other**
Copy template
```
cp -a layouts/partials/simple layouts/partials/awesome
cp static/css/templates/simple.css static/css/templates/awesome.css
```


### Contributing

If you find a bug or have an idea for a feature, feel free to use the [issue tracker](/https://github.com/andresmazzo/gohugo-theme-comingsoon) to let me know.