# Resume

<b><font size="+3">Recruiters:</font> This is just a sample. My updated resume can be found [on my Google Drive](https://drive.google.com/open?id=0B1I7ETQXT-TFR3NBQVVwazhnb2c).</b>

Simple, responsive and printable resume in HTML and CSS made dynamic using Jekyll.

http://aviaryan.github.io/resume

All resume content is stored in yaml files (skills.yml, projects.yml ..) in the `_data` directory. 

Changing order of categories in resume is easy. :wink: Just change the include orders in `index.html`
```html
{% include education.html %}
{% include skills.html %}
{% include projects.html %}
{% include awards.html %}
{% include work.html %}
{% include social.html %}
{% include contact.html %}
{% include references.html %}
```

For local development, create an empty file named `local` in project root. This will ensure that local resources are loaded by Jekyll instead of CDN's.
