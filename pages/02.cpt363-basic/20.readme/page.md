---
title: Read Me
published: true
hide_page_title: true
---

## Create, Publish, Share and Collaborate using the Grav Open MultiCourse Hub!  

1. Create a new [Git](https://git-scm.com/) repository (hosted on [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/) or your own server) with at least one commit.
2. Set up Git Sync in the Admin Panel for step-by-step instructions – on Grav 2 it has its own [Git Sync](../../admin/plugin/git-sync) menu item, and on Grav 1.7 it's under Plugins → [Git Sync](../../admin/plugins/git-sync).
3. Configure the [Git Sync Link](../../admin/themes/mytheme) settings in the Theme options to change the display and functionality of the automatically displayed Git Sync Link.

## Extend the Capabilities of Your Learning Management System (LMS)  

By adding the URL parameter (i.e. flag) `chromeless:true` to any Open MultiCourse Hub page you can display that page's content without the global header image, site navigation bar, sidebar and footer - a great way to seamlessly embed Open MultiCourse Hub pages into other systems.  

For example, the URL [demo.hibbittsdesign.org/grav-open-multi-course-hub/cpt363-basic/schedule](https://demo.hibbittsdesign.org/grav-open-multi-course-hub/cpt363-basic/schedule) displays the standard Open MultiCourse Hub page but the URL [demo.hibbittsdesign.org/grav-open-multi-course-hub/cpt363-basic/schedule/chromeless:true](https://demo.hibbittsdesign.org/grav-open-multi-course-hub/cpt363-basic/schedule/chromeless:true) will only display that page's content. Any links between Open MultiCourse Hub pages will result in pages being displayed in the same manner.

## Modules, a Course Blog, or Weekly Units

Each course can be organised its own way. Modules work as in Grav Helios Course Hub: a Modules page with a card for each module, a list of modules beside every module page, and Previous and Next buttons through every module and page. A course blog holds news, tips and reflections alongside the modules, and a blog page can instead list weekly units, newest first.

The example courses show each one: [CPT363-1](/cpt363-basic/modules) is organised by modules, [CPT363-2](/cpt363-intermediate/blog) adds a course blog, and [CPT363-3](/cpt363-advanced/weekly-units) is organised by weekly units.

## Bring Courses Over from Your LMS

Have a course in Canvas, Moodle, Brightspace, or Blackboard? Export it as a Common Cartridge file, and the free [Common Cartridge Converter](https://common-cartridge-converter.hibbittsdesign.org/) (beta) turns it into a new course for this site, organised by modules – see [an example conversion](https://demo.hibbittsdesign.org/grav-open-course-hub-it2dda/).

## What Else Can the Open MultiCourse Hub do for You? ##
Learn more about the capabilities of the Open MultiCourse Hub project in its [README on GitHub](https://github.com/hibbitts-design/grav-skeleton-multicourse-hub#readme).

<hr>

Want to no longer display this page on your site?  
Delete the page 'Read Me' in your [Admin Pages panel](../../admin/pages) or set the page's 'Published' option under the 'Options' Tab to 'No'.
