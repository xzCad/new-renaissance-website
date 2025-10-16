---
layout: home
permalink: "/"
title: "Ultima Online New Renaissance"
description: "A custom Renaissance era Ultima Online free shard. Classic gameplay, custom content, and an active community awaits you in Britannia."
header_transparent: true
meta_title: Ultima Online - New Renaissance

hero:
  enabled: true
  heading: "Welcome to New Renaissance"
  sub_heading: "Experience Ultima Online as it was meant to be. Renaissance era mechanics, custom content, and a thriving community await you in Britannia."
  text_color: "#FFFFFF"
  background_color: "#1d2830"
  background_gradient: true
  background_image: "/assets/images/gen/home/home-1-large.webp"
  background_image_blend_mode: overlay
  fullscreen_mobile: true
  fullscreen_desktop: false
  height: "660px"
  buttons:
    enabled: true
    list:
      - text: "Download Client"
        url: "https://github.com/xzCad/newrenaissance-launcher/releases/download/Installer/New.Renaissance.exe"
        external: true
        fa_icon: "fas fa-download"
        size: large
        outline: false
        style: "primary"
      - text: "Getting Started"
        url: "/getting-started"
        external: false
        fa_icon: "fas fa-book"
        size: large
        outline: true
        style: "light"

services:
  enabled: true
  heading: "Server Features"
  sub_heading: "What makes New Renaissance unique"
  limit: 6
  sort: "weight"
  view_more_button_text: "View All Features"
  view_more_button_link: "/services"
  prevent_click: false

intro:
  enabled: true
  align: left
  image: "/assets/images/gen/content/content-5-thumbnail.webp"
  heading: "Classic Renaissance Era Gameplay"
  sub_heading: "We've carefully recreated the golden age of Ultima Online with modern enhancements. Join hundreds of players in a living, breathing world of adventure."
  features:
    enabled: true
    list:
      - text: "Authentic Renaissance era mechanics and skill system"
        fa_icon: "fas fa-check"
      - text: "Active staff and regular events"
        fa_icon: "fas fa-check"
      - text: "Balanced PvP and PvE experiences"
        fa_icon: "fas fa-check"
  buttons:
    enabled: true
    list:
      - text: "Learn More"
        url: "/about"
        external: false
        fa_icon: ""
        size: large
        outline: false
        style: "primary"

partners:
  enabled: false
  limit: 5
  sort: "weight"

projects:
  enabled: true
  heading: "Community Highlights"
  sub_heading: "Recent events and player achievements"
  limit: 2
  columns: 2
  sort: "weight"
  view_more_button_text: "View Gallery"
  view_more_button_link: "/projects"
  prevent_click: false

outro:
  enabled: true
  align: center
  image: false
  heading: "Ready to Begin Your Journey?"
  sub_heading: "Download the client and connect to New Renaissance today. Adventure awaits in Britannia!"
  features:
    enabled: false
  buttons:
    enabled: true
    list:
      - text: "Download Now"
        url: "https://github.com/xzCad/newrenaissance-launcher/releases/download/Installer/New.Renaissance.exe"
        external: true
        size: "large"
        style: "primary"
      - text: "Join Discord"
        url: "/contact"
        external: false
        size: "large"
        style: "light"

posts:
  enabled: true
  heading: "Latest News & Updates"
  sub_heading: "Stay informed about server updates, events, and announcements"
  limit: 3
  columns: 3
  sort: "date"
  view_more_button_text: "View All News"
  view_more_button_link: "/blog"
  prevent_click: false
---