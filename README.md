# HAX Portfolio Site Workshop

In this workshop we'll

- Learn how to use the HAX web editor to build a documentation or portfolio website
- Learn how to install HAX cli locally on your machine to build sites
- Publish sites from your computer to https://surge.sh for free, static website hosting
- Learn how to join the HAX community

# What is HAX
- HAX is a modern web site building editor founded at Penn State
- You can quickly build websites that update instantly
- All files are static and work anywhere! Download and take with you

# Getting started with HAX.psu

- Go to https://hax.psu.edu and click Login
- Not part of Penn State? Try HAX using https://hax.cloud

1. Create a new site
2. Select the type of site (This just selects a theme which can be changed later). Let's pick Course for documentation
3. Name your site and pop the confetti, you've started a new website with HAX!

## Common operations
- Add pages by hitting Add Page
- Edit pages by navigating to them and hitting edit in the top bar
- To change the title, click on the "Select to edit Page details" label and work with the left settings panel
- Click below to start writing as you normally would in a word processor. You are writing HTML!

## Merlin knows all
- Clicking on Merlin, the search bar in the top right or by typing `/` on a blank paragraph
- Merlin allows you to upload files, insert blocks, download your site and more!
- Let's insert an image using the Magic File Wand program. Click the program and select an image to upload
- Merlin will analyze the upload and present options for how to present it

## Site Actions - Changing the theme
- You can change your theme and other settings under Site Actions -> Site Settings
- This lets you modify SEO settings, the theme, some color values and more.
- Try changing the theme to Clean One or Clean Portfolio Theme

## Outline Designer - organize pages quickly
- Located under Site Actions -> Outline Designer
- Outline Designer allows you to quickly build out the hierarchy of your website

# Now you have all the tools to build out your site
- For a walk through we'll build a project Documentation site for a hackathon
- Use HAX to build a doc site to promote your project this weekend!
- Try using the `clean-one` or `clean-two` themes, as these are primed for documentation
- We also have several PSU style themes as well as portfolios and some silly stuff too

# Install HAX CLI to build sites on your machine without hax.psu.edu

This is how the team builds out sites and works on the platform locally.

```bash
# this allows you to then use hax command
npm install @haxtheweb/create --global
```

If you don't have npm / nodejs installed you can do so here: https://nodejs.org/ then run the previous line again

- Navigate to the folder you want to build a site in
- run `hax start` and see the colorful ascii art load up
- Let's walk through building a site out using the CLI
- Name your site and select a theme
- A local server will launch so you can start building out your site but on your own file system!

## Publishing to surge.sh
- Close the process in the terminal for your hax site
- type `hax site` while in the folder containing your site
- options related to the site will show up; select publish
- step through the surge.sh publishing steps
- You'll get a URL which you can go to

## Party time!
- You now have the publishing power of hax.psu.edu but on your computer!
- It pairs great with terminal based AI programs like [warp](https://warp.dev/)!

# Join HAX Club
- HAX Club will be sprinting on [issues](https://github.com/haxtheweb/issues/issues) in the platform and on-boarding people to learn open source web developmenting
- Contribute to HAX and learn open source development every Monday 7pm Ag Engineering 121

Congrats, you have a site that's kept up to date by the HAX content delivery network!

# Learn more
- https://haxtheweb.org
