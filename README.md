# Cancer Epi Microbiome Workshop

This repository contains the website for the Cancer Epidemiology & Microbiome Workshop.

## About

Workshop on cancer epidemiology and microbiome research methods.

## Testing Locally

To test the website locally, install Jekyll and run:

```bash
bundle install
bundle exec jekyll serve --force_polling --port 4000
```

Then visit `http://localhost:4000/cancer_epi_microbiome_course/` in your browser.

## Structure

- `_config.yml`: Main site configuration
- `workshops/`: Workshop content and materials
- `_instructors/`: Instructor profiles
- `_posts/`: News and updates
- `Resources/`: Additional resources

## Customization

This site is built using Jekyll with the [Bulma Clean Theme](https://github.com/chrisrhymes/bulma-clean-theme).

To customize:
1. Edit `_config.yml` for site-wide settings
2. Add workshop content in the `workshops/` directory
3. Add instructor information in `_instructors/`
4. Update news items in `_posts/`

## Deployment

This site is designed to be deployed on GitHub Pages. Make sure to:
1. Push this repository to GitHub
2. Enable GitHub Pages in repository settings
3. Set the source to the main branch

## Support

For issues with Jekyll or GitHub Pages, see:
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
