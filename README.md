# HAX Portfolio Site Workshop

Welcome! In this workshop, you'll learn how to install the HAX CLI and create a 3-page portfolio site from scratch.

## Prerequisites

- A computer with internet access
- Basic familiarity with using the command line/terminal

## Part 1: Installing HAX CLI

### Step 1: Install Node.js (if not already installed)

HAX requires Node.js version 18 or higher.

1. Check if you have Node.js installed:
   ```bash
   node --version
   ```

2. If you don't have Node.js, download and install it from [nodejs.org](https://nodejs.org/)

### Step 2: Install HAX CLI

Install the HAX CLI globally using npm:

```bash
npm install -global @haxtheweb/create
```

### Step 3: Verify Installation

Check that HAX is installed correctly:

```bash
hax --version
```

You should see the version number displayed.

## Part 2: Creating Your Portfolio Site

### Step 1: Create a New HAX Site

1. Navigate to where you want to create your site:
   ```bash
   cd ~/Documents
   ```

2. Create a new site called "my-portfolio":
   ```bash
   hax site
   ```

3. When prompted, name your site: `my-portfolio`

4. When asked to select a theme, choose: `portfolio`

### Step 2: Start the Development Server

Navigate into your new site and start the server:

```bash
cd my-portfolio
hax start
```

Your site will open in your default browser at `http://localhost:3000`

## Part 3: Understanding the HAX Editor

Before we create pages, let's understand the HAX interface:

- **Edit Mode**: Click the pencil icon to enter edit mode
- **Block Menu**: Click the `+` button to add new content blocks
- **Block Actions**: Hover over blocks to see edit, delete, and move options
- **Settings Panel**: Click on a block to see its properties in the right panel
- **Save**: Click save and the HTML of the page is written to the system
- **Add Page**: Click to add a blank new page

## Part 4: Creating Your Three Pages

### Page 1: About

- Click the first page in the site
- Click edit in the top left
- Click the "Select to edit Page details" area that appear just below the page title
- Use this to rename the page or change details about the page

#### Sample Content for About Page:

**Add a Heading:**
- click a paragraph or empty area just below the page details.
- type the `/` key to pull up "merlin". Merlin lets you do any operation in HAX!
- type heading to add an h2. Or type `##` followed by a spacebar to make a quick heading
- Type: `About Me`

**Add a Paragraph:**
- Hit enter to move down a line and create a paragraph
   ```
   Hi, I'm [Your Name]! I'm a passionate web developer and designer who loves creating meaningful digital experiences. I believe in the power of open source technology and continuous learning.
   ```

**Add an Image:**
- Click Merlin in the top right
- Select the "Magic File Wand" program
- Find an image on your computer or download and use https://placekitten.com/400/300
- Add it to the page

**Add More Content:**
1. Add another paragraph block
2. Type:
   ```
   I specialize in web development, with experience in HTML, CSS, JavaScript, and modern web components. When I'm not coding, you can find me exploring new technologies, contributing to open source projects, or enjoying the outdoors.
   ```

# Other content to try out
- Click Blocks and explore the dozens of page blocks you can add with HAX
- Pasting a youtube link into a blank paragraph will embed it as a video or use the block
- Click on the block in the page to see and edit the block's settings

When your ready to save your work, hit save and the content will immediately be updated and published for others to see!

## Resources

- HAX Documentation: Check the official docs for more features
- HAX Community: Join the community for support and inspiration
- Web Components: Learn more about the technology powering HAX

