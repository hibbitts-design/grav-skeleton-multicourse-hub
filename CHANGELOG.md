# v2.8.4
## XX/XX/2026

1. [](#improved)
    * Asset timestamps turned on (Enable Timestamps on Assets), so readers' browsers load updated theme and plugin styles and scripts right after an update, instead of keeping old copies for up to a week

# v2.8.3
## 10/18/2026

1. [](#improved)
    * Update to Bootstrap4 Open Matter 6.4.10: badges on module cards, captions for images in plain Markdown, an image height limit for presenting, a clearer Topics index, better contrast for green and purple badges, tapping an image to see it larger, and complete French and German translations
    * Example content: the Welcome module in CPT363-1 and CPT363-2 has a "Start here" badge on its card, a captioned photo, and text shown only on the site or only when embedded ([hideifembedded] and [showifembedded])
    * Example content: the CPT363-3 course card's "New Section" badge is purple, so it stands apart from the green "Start here" module badges

# v2.8.2
## 10/16/2026

1. [](#improved)
    * Update to Bootstrap4 Open Matter 6.4.6: a "Skip to content" link for keyboard users, past the NavBar to the page content
1. [](#bugfix)
    * UX Techniques Guide (CPT363-2 and CPT363-3): the Job Stories page has its own title, not Interviews

# v2.8.1
## 10/15/2026

1. [](#improved)
    * Update to Bootstrap4 Open Matter 6.4.5: Yes/No switches show their labels in Admin on more hosts, links work in chromeless mode, the site name links to the home page from blog posts, embedded module pages leave out their Previous and Next buttons, and RSS Feeds pages show their preview text and images again
    * CPT363-3 (weekly units): the Syllabus is published, and Topics and UX News are unpublished, for a shorter menu
    * UX News feeds: Smashing Magazine and Nielsen Norman Group replace A List Apart and UX Matters, whose feed stopped updating in 2024 (Twig Feeds stays off until enabled)
    * README: the Topics index example points to CPT363-2, and Resources pages are described as optional

# v2.8.0
## 10/13/2026

1. [](#new)
    * Example courses by format: modules (CPT363-1), modules with a blog (CPT363-2), and weekly units (CPT363-3)
    * Includes the Taxonomy List, Archives and Feed plugins for the blog sidebar, and Page TOC again, for each module page's sections
1. [](#improved)
    * Each Home page links straight to this week's and next week's unit or module
    * Looking Ahead to Next Week slides links have an icon, as on the Schedule
    * Course cards, Read Me pages and README describe each format, and importing a course from an LMS
    * Clearer descriptions for Modules 9, 12 and 13; CPT363-3's unused Modules removed
    * Update to Bootstrap4 Open Matter 6.4.0

# v2.7.0
## 10/12/2026

1. [](#new)
    * Each course has a separate Weekly Units page for its weekly units, and its Home page shows just the announcement, this week's reminders and next week's preparations, closer to the Grav Helios Course Hub home page
    * CPT363-2 is now organised by modules, as a live example: its Modules page replaces its weekly units, with its Schedule and Topics linking to the modules, and its Topics page is published
1. [](#improved)
    * Weekly units are now at weekly-units/week-01 and so on, with the Schedule and Topics links updated, and Weekly Units comes first in each course's menu
    * The Page TOC plugin is no longer included, as Bootstrap4 Open Matter 6.3.1 no longer shows an "On this page" list on module pages

# v2.6.0
## 10/11/2026

1. [](#new)
    * The Page TOC plugin is included, for the "On this page" list on module pages (version 3.2.5 in the Grav 1.7 package)
1. [](#improved)
    * Weekly pages renamed from `module-NN` to `week-NN`, so they aren't confused with modules
    * CPT363-3's Module Readings renamed to Weekly Readings, with "Week N" titles

# v2.5.6
## 10/10/2026

1. [](#bugfix)
    * CPT363-2's UX Techniques Guide uses the accordion page type, so it shows as an accordion when published

# v2.5.5
## 10/10/2026

1. [](#improved)
    * The header image shows on home pages only ("Standard on home pages, hidden elsewhere"), so other pages open straight onto their content
    * My Theme reuses the Bootstrap4 Open Matter theme options instead of a copy, so they stay up to date; the README shows how to update an existing site
    * Update to Bootstrap4 Open Matter 6.2.0

# v2.5.4
## 10/10/2026

1. [](#improved)
    * Slate blue (#3b5682) with Tinted as the default NavBar colour and look – a calm, neutral default that suits the header images and leaves room for an institution's own colour
    * Updated screenshots

# v2.5.3
## 10/09/2026

1. [](#improved)
    * No "Setup Git Sync" link is shown before Git Sync is connected to a repository; the Read Me page and README say where to set it up in the Admin Panel (its own menu item in Grav 2, or Plugins → Git Sync in Grav 1.7)
    * Update to Bootstrap4 Open Matter 6.1.7

# v2.5.2
## 10/08/2026

1. [](#improved)
    * Plum (#7c1557) with Tinted (strong) as the default NavBar colour and look
    * The bootstrap4-open-matter theme config now matches mytheme's look (2026 Modern, Tinted (strong) NavBar, plum)
    * Update to Bootstrap4 Open Matter 6.1.6

# v2.5.1
## 10/07/2026

1. [](#new)
    * New sites use the 2026 Modern Theme Style with the Tinted NavBar Look (Bootstrap4 Open Matter 6.1.0)
1. [](#improved)
    * Add GitHub-style alerts to the Grav 1.7 version (GitHub Markdown Alerts plugin 1.1.1)
    * Add the 2026 Modern and NavBar Look options to the mytheme blueprints
    * Update README

# v2.5.0
## 10/04/2026

1. [](#new)
    * Add course search (SimpleSearch plugin)
    * Add GitHub-style alerts to the Grav 2.0 version (GitHub Markdown Alerts plugin)
1. [](#improved)
    * Update to Bootstrap4 Open Matter 6.0.2
    * Use the standard header image on home pages and the slim one elsewhere, and hide Syndicate links in the demo
    * Use the `[topics]` shortcode for the example Topics pages
    * Add example announcement, course card badge, objectives, references and accessible embed titles to the demo
    * Point documentation links to the README on GitHub and update demo links
    * Refresh the Courses homepage intro and add example instructor lines
    * Update README for the new features
1. [](#bugfix)
    * Use Grav's default jQuery 3 (jQuery 2.1.4 was removed in Grav 2.0.14)
    * Fix the "Display in course list" setting in the example courses

# v2.1.1
## 10/02/2026

1. [](#bugfix)
    * Fix each course's LMS Home page so it shows that course's reminders and preparations
    * Replace the Guerrilla UX Testing reading, no longer available, with the Usability Geek article
1. [](#improved)
    * Rewrite README in streamlined style with homepage and interior page screenshots

# v2.1.0
## 10/01/2026

1. [](#improved)
    * Remove Custom Presentation Link Text option from inherited theme, as legacy Presentation plugin support has been removed
    * Replace CPT 363 Advanced example presentations with Google Slides placeholders, as used in the other example courses, and remove the Add Presentation and Add Presentations List Admin buttons
    * Remove unused Presentation plugin configuration
    * Remove legacy NextGen Editor configuration and README mention

# v2.0.8
## 08/24/2026

1. [](#new)
    * Update default skeleton download to Grav 2.0

1. [](#improved)
    * Add 1.7|2.0 compatibility flags to default inherited theme

# v2.0.7
## 06/18/2026

1. [](#improved)
    * Updated to Grav 1.7.53

# v2.0.6
## 06/10/2026

1. [](#improved)
    * Added default config for Login plugin to not use built-in CSS

# v2.0.5
## 05/19/2026

1. [](#improved)
    * Restore Grav 1.7 Custom Admin plugin (Customadmin Grav2 no longer needed)

# v2.0.4
## 05/11/2026

1. [](#bugfix)
    * Fix ChangeLog formatting issue

# v2.0.3
## 05/11/2026

1. [](#improved)
    * Update config to support Off/On/Auto (System) setting for bootstrap4-open-matter and mytheme

# v2.0.2
## 05/08/2026

1. [](#improved)
    * Updated skeleton screenshot

# v2.0.1
## 04/22/2026

1. [](#improved)
    * Updated to Bootstrap4 Open Matter v5.0.2
    * Streamlined dependencies to improve Grav 2 compatibility
    * Updated Customadmin plugin to custom Customadmin Grav2 with Admin2 (Grav 2) CSS and JS support, maintaining full backward compatibility with Admin1

# v2.0.0
## 04/21/2026

1. [](#improved)
    * Updated to Bootstrap4 Open Matter v5.0.0

# v1.1.2
## 03/26/2026

1. [](#improved)
    * Updated to Grav 1.7.49.5

# v1.1.1
## 09/01/2025

1. [](#improved)
    * Included example CSS for light and dark theme support in custom.css file

# v1.1.0
## 08/31/2025

1. [](#improved)
    * Updated to Grav 1.7.49.2 and Bootstrap4 Open Matter v4.0.1
    * Updated example CSS for light and dark theme support for custom.css file
    * Updated default demo pages

# v1.0.14
## 08/25/2025

1. [](#improved)
    * Changed skeleton author information to HibbittsDesign.org
    * Updated default demo pages

# v1.0.13
## 07/17/2024

1. [](#improved)
    * Updated to Grav 1.7.46

# v1.0.12
## 10/12/2023

1. [](#improved)
    * Updated to Grav 1.7.43

1. [](#bugfix)   
    * Removed example Twitter(X) in sidebar

# v1.0.11
## 07/05/2023

1. [](#improved)
    * Updated to Grav 1.7.42.1

# v1.0.10
## 10/14/2022

1. [](#improved)
    * Updated to Grav 1.7.37.1
    
# v1.0.9
## 07/06/2022

1. [](#improved)
    * Updated to Grav 1.7.34

# v1.0.8
## 02/15/2022

1. [](#improved)
    * Updated to Grav 1.7.30

# v1.0.7
## 09/25/2021

1. [](#improved)
    * Updated to Grav 1.7.22 and Bootstrap4 Open Matter v3.7.9

# v1.0.6
## 06/16/2021

1. [](#improved)
    * Updated to Grav 1.7.17 and Bootstrap4 Open Matter v3.7.7

# v1.0.5
## 04/19/2021

1. [](#improved)
    * Updated to Grav 1.7.12

# v1.0.4
## 03/20/2021

1. [](#improved)
    * Updated default demo pages

# v1.0.3
## 02/27/2021

1. [](#improved)
    * Updated skeleton title and description

# v1.0.2
## 02/26/2021

1. [](#improved)
    * Updated site name
    * Updated skeleton screenshot

# v1.0.1
## 02/25/2021

1. [](#bugfix)
    * Corrected demo URL for skeleton

# v1.0.0
## 02/25/2021

1. [](#new)
    * ChangeLog started...
