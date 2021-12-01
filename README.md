# Site Cours Craft 2021

Site construit avec Craft CMS 2021-2022

## CHAMPS

### Common

- **commonTitle**: textfield (128)
- **commonIntro**: textfield (300)
- **commonBody**: redactor (full)

### Blog

- **blogImage**: assets(1) connected to `volumesBlogImages`
- **blogStyles**: categories(n) connected to `styles`

### About page

- **aboutImage**: assets(1) connected to `volumesPagesImages`
- **aboutSkills**: matrix (@TODO)

### Mainnav

- **mainnavLabel**: textfield (30)
- **mainnavEntry**: entries (1, "Singles")

### Social media

- **facebookUrl**: textfield (256)
- **twitterUrl**: textfield (256)
- **instragramUrl**: textfield (256)


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
- **aboutImage** @TODO
- **commonBody**
- **aboutSkills** @TODO

### Blogposts: `blog` channel

- **title**: auto
- **blogImage**
- **commonIntro**
- **commonBody**

### Mainnav: `mainnav` structure

- **title**: hidden and set to `mainnavLabel`
- **mainnavLabel**
- **mainnavEntry**

## GLOBALS

### Social media `socialmedia`

- **facebookUrl**
- **twitterUrl**
- **instragramUrl**

## CATEGORIES

### styles `styles`

- **title**: auto