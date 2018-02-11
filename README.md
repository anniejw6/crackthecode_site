# Crack the Code

This template is drawn from [Project Zeppelin](https://github.com/gdg-x/zeppelin).

To build this site, clone this repository and run

```
jekyll serve
```

`*.md` pages in the home directory are pages (e.g., about speakers, for registration).

Note: when we're reading to add the schedule back, in `schedule.html`:

* Change `schedule.md` to `schedule.html`
* Change `layout: post` to `layout: default`
* Add `{% include top-section.html %} {% include schedule.html %}` to the body