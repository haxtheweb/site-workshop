# HAX Portfolio Site Workshop

In this workshop we'll

- Learn how to use the HAX web editor to build a documentation or portfolio website
- Learn how to install HAX cli locally on your machine to build sites
- Publish sites from your computer to https://surge.sh for free, static website hosting
- Learn how to get involved with the HAX community

# What is HAX
- HAX is a modern web site building editor founded at Penn State
- You can quickly build websites that you can download and take with you
- HAX sites have no need for a backend other than for editing them. All files are static and work anywhere!

# Getting started with HAX.psu

- Go to https://hax.psu.edu and click Login
- Not part of Penn State? Try HAX our using https://hax.cloud

1. Create a new site
2. Select the type of site (This just selects a theme which can be changed later)
3. Name your site and pop the confetti, you've deployed a new website with HAX!

## Common operations
- Add pages by hitting add page.
- Edit pages by clicking the edit button. You can now click and modify the content of the page
- If you want to change the title, click on the "Select to edit Page details" label, then you can modify settings in the left hand panel
- Clicking on any block in the page allows you to have additional options of things to do with that block

## Merlin knows all
- Clicking on Merlin or typing `/` on a blank paragraph can call up Merlin
- Merlin allows you to upload files, insert blocks, download your site and more
- Start typing the thing you want to do into Merlin to watch it filter what's possible

## Site Actions
- You can change your theme and other settings under Site Actions -> Site Settings
- This lets you modify SEO settings, the theme, some color values and more.
- Try changing between the different themes now

## Outline Designer
- Located under Site Actions -> Outline Designer
- Outline Designer allows you to quickly build out the hierarchy of your website
- Let's add some pages and rename them quickly here

# Now it's your turn to build whatever you want
- Use HAX to build a small documentation site for your projects this weekend
- Try using the `clean-one` or `clean-two` themes, as these are primed for documentation
- Using the outline designer, make a pages for Who your team is, Project goals, Code, Resources and anything else you want
- Now let's edit the content and add images using Merlin's Magic File Wand

# Installing HAX CLI to build sites on your machine

Running 
```
# this allows you to then use hax command
npm install @haxtheweb/create --global
# then run this for interactive prompt
hax start
```

If you don't have npm / nodejs installed you can do so here: https://nodejs.org/ then run the previous line

- Walk through creating a site with the `hax start` or `hax site` command
- Name your site and select the theme
- A local server will launch so you can start building out your site but on your own file system!

## Publishing to surge.sh
- Close the process in the terminal for your hax site
- type `hax site` while in the folder containing your site
- options related to the site will show up; select publish
- step through the surge.sh publishing steps
- You'll get a URL which you can go to

Congrats, you have a site that's kept up to date by the HAX content delivery network!
