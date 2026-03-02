# BlankVersaHugo
A BlankVersa website built on Hugo. Using GitHub Actions to automate website 
building when new markdown articles are written. Mixture of blog and static 
sites for specific tools.

## TODO
[ ] Make theme
    [ ] Adjust nav and updates scrollable
[ ] Migrate articles
[ ] Set up table of contents on right side
[ ] Set Up GitHub Actions
[ ] Tools
    [ ] Quick Search
    [ ] Time Converter
    [ ] Add Tutorial
[ ] How do you make breadcrumbs?

## Notes
Layout - Everything will have `baseof.html`. This should contain your header, 
nav, footer, anything that surrounds the content should be here

Home - The landing page of the website, have unique content here

Section - The landing site for a particular set of pages. For example, personal, 
blog, tools

Page - The individual post by the associated section, could be a blog post or a 
static site entry

