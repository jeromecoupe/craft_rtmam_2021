# Site Cours Craft 2021

Site construit avec Craft CMS 2021-2022

## CHAMPS

### Common

- **commonTitle**: textfield (128)
- **commonIntro**: textfield (300)
- **commonBody**: redactor (full)

### Blog

- **blogImage**: assets(1) connected to `volumesBlogImages`

### About page

- **aboutImage**: assets(1) connected to `volumesPagesImages`
- **aboutSkills**: matrix (@TODO)

## SECTIONS

### Home page: `pageHome` single

- **commonTitle**
- **commonIntro**

### Blog page: `pageBlog` single

- **commonTitle**
- **commonIntro**

### About page: `pageAbout` single

- **commonTitle**
- **commonIntro**
- **aboutImage**
- **commonBody**
- **aboutSkills**

### Blogposts: `blog` channel

- **title**: auto
- **blogImage**
- **commonIntro**
- **commonBody**
