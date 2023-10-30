Webfolio Website
==========================
Personal website to show off my projects, info about me, and cool stuff I do. My webfolio will provide links to my GitHub profile, repositories, my resume, socials, and my *possible* photography website.

main-master-redo
---
This version of the code completely restructures the base code for the website. Rather than relying on a series of pages, the webfolio will rely on a single page. The purpose of this is to allow for future recreations of the webfolio using systems such as React to improve the abilities of the site is needed as all the information would be sotred under a single universal index.html.

## Legacy Code
Legacy code is hidden with comments. The last versions of the legacy code that were used:

<blockquote>
<h3>ContactLink Branch</h3>
The Contact Link is supposed to be linked from an NFC chip allowing my contact information to be shared on mobile browsers.
</blockquote>

This code is outdated but some of its fuctionality can still be reused later.

<!--

v0.0.2 ContactLink branch
----------------------------------------

## Objective

The Contact Link is supposed to be linked from an NFC chip allowing my contact information to be shared on mobile browsers.

## Organization

Each button link is structured under a div with the class *contactButton* and storing the actual link inside it. The link itself stores the *h4* tag that is the type of link and *p* containing information for how to search the information manually.
Example:
    Instagram
    @churuizramos

For the [Add Contact] button, rather than a link, the button executes a download command for a VCF file storing said contact information. Reasearch at: https://stackoverflow.com/questions/8669912/add-a-contact-to-the-mobile-device-address-book-from-an-html-webpage.

VCF file is labeled [contactDownload.vcf]

## Notes

Color scheme used on this page would work well in the rest of the website. Link at the bottom will be used to access the main website.

v0.0.1c Rewrite syntax fix
----------------------------------------

## Changes
ID and Class tags were incorrectly declared in HTML source

v0.0.1b Initial Code Rewrite (7-28-2023)
----------------------------------------

## Changes

Rewrote initial code. Changed structure of information. Focusing primarily on the setup of the main page for the website.

## Reason for changes

Original code was cluttered and prepped for an illogical use basis.


v0.0.1 Initial Code State (7-5-2023)
----------------------------------------

This is a static basis including most of the files that could end up being used to create the website. Pages and their information still need to be fleshed out completely. New system should be utilized to simplify the page creation process.

-->