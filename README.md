# Jinja Template

> A curated list with Jinja2 templates provided by AppSeed from well-known, modern UI Kits - Free and commercial projects.

<br />

## What is [Jinja2](https://jinja.palletsprojects.com/en/2.11.x/)

Jinja is a Python template engine used to generate HTML or XML returned to the user via an HTTP response.
For those who have not been exposed to a templating language before, such languages essentially contain variables as well as some programming logic, which when evaluated (or rendered into HTML) are replaced with actual values.

This modern template engine, basically help us to win time. By using it we get `out-of-the-box` some really nice features:

- *Template Inheritance* - This feature helps us to generate new pages starting from a base template that we inherit a common structure.
- *Sandboxed Execution* - It provides a protected framework for automation of testing programs, whose behavior is unknown and must be investigated.
- *HTML Escaping* - Jinja2 has a powerful automatic HTML Escaping, which helps to prevent Cross-site Scripting (XSS Attack). There are special characters like >,<,&, etc. which carry special meanings in the templates. So, if you want to use them as regular text in your documents then, replace them with entities. Not doing so might lead to XSS-Attack.

<br />

> Jinja2 in action

Before using Jinja, of course we need to install it using PIP:

```bash
$ pip install jinja2
```

Once we have the Jinja package available, we can warm up with a simple code snippet written in the python terminal:

```python
>>> from jinja2 import Template
>>> t = Template("Hello {{ token }}!")
>>> t.render(token="Jinja2")
u'Hello Jinja2!'
```

For more information about this template engine please access the links:

- [Jinja2](https://palletsprojects.com/p/jinja/) - official website
- [Jinja2 Documentation](https://jinja.palletsprojects.com/en/2.11.x/)

<br />

## Jinja2 Templates - Open-source

> Free Jinja templates that can be used for hobby & commercial projects.

<br />

| Item | Provider | License | - | - |
| --- | --- | --- | --- | --- |
Black Dashboard | Creative-Tim | MIT | [Demo](https://jinja2-black-dashboard.appseed.us/) | [Sources](https://github.com/app-generator/jinja2-black-dashboard)
Jinja AdminLTE | ColorLb | MIT | [Demo](https://jinja2-adminlte.appseed.us/) | [Sources](https://github.com/app-generator/jinja2-adminlte)
Jinja Adminator | ColorLb | MIT | [Demo](https://jinja2-adminator.appseed.us/) | [Sources](https://github.com/app-generator/jinja2-adminator)
Jinja GradientAble | CodedThemes | MIT | [Demo](https://jinja2-gradientable.appseed.us/) | [Sources](https://github.com/app-generator/jinja2-gradientable)
Jinja CoreUI | CoreUI | MIT | [Demo](https://theme-jinja2-coreui.appseed.us/) | [Sources](https://github.com/app-generator/theme-jinja2-coreui)
Jinja AdminT | YooKits | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | [Demo](https://theme-jinja2-admint.appseed.us/) | [Sources](https://github.com/app-generator/theme-jinja2-admint)
Jinja Quick UI | Webpixels | MIT | [Demo](https://theme-jinja2-quick-uikit.appseed.us/) | [Sources](https://github.com/app-generator/theme-jinja2-quick-uikit)

<br />

## Jinja2 Templates - Commercial

> Jinja templates that require a license.

<br />

| Item | Provider | License | - | - |
| --- | --- | --- | --- | --- |
Argon Dashboard PRO | Creative-Tim | EULA | [Demo](https://theme-jinja2-argon-dashboard-pro.appseed.us/) | [Github](https://github.com/app-generator/theme-jinja2-argon-dashboard-pro)
Material Dashboard PRO | Creative-Tim | EULA | [Demo](https://theme-jinja2-material-dashboard-pro.appseed.us/) | [Github](https://github.com/app-generator/theme-jinja2-material-dashboard-pro)
Black Dashboard PRO | Creative-Tim | EULA | [Demo](https://theme-jinja2-black-dashboard-pro.appseed.us/) | [Github](https://github.com/app-generator/theme-jinja2-black-dashboard-pro)
Material PRO Wpx | WrapPixel | EULA | [Demo](https://jinja2-material-dashboard-wpx-pro.appseed.us/) | [Github](https://github.com/app-generator/jinja2-material-dashboard-wpx-pro)

<br />

---
Jinja Template - A curated list. Index provided by [AppSeed](https://appseed.us/)
