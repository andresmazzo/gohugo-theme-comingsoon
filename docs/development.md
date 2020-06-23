## Development

### Project Structure
Code organization is defined by gohugo themes. But internally we could append the following:

**Components**
Inside `layouts/partials` there is a `components` directory that includes generic html, like countdown or subscription. They are used by templates, which each one adjust style via css classes.

**Templates**
The funny part. See `layouts/partials` and `static/css/templates`. Both one dir per template.



### Guides

#### Update git submodule
```
git submodule update --recursive --remote
```

#### Create template from scratch
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
mkdir your-template-name
cd your-template-name
vim main.css
...
vim variables.css
```

#### Create template based on other
Copy template
```
cp -a layouts/partials/templates/simple layouts/partials/templates/awesome
cp -a static/css/templates/simple static/css/templates/awesome
```
