---
# PubConf Events are defined by this markdown frontmatter. This template
# contains all the supported fields and descriptions.
#
layout: "event-2026"

# Full title of the event. Will be used in meta tags. Usually "PubConf City Year"
title: PubConf London 2026

# ISO8601 Date for the starting time of the event. Make sure the offset is in the
# event location timezone.
date: 2026-01-30T19:00:00Z

# ISO8601 Date for the ending time of the event.
end_date: 2026-01-30T23:59:00Z

# ISO8601 Date (without offset) for the local time of the event. This is used
# for display because dates are hard.
local_time: 2026-01-30T19:00

# Tickets object. Comment this out until tickets are ready to be sold.
# tickets:
#   # External URL to purchase tickets. Eventbrite, etc.
#   url: https://www.eventbrite.co.uk/e/pubconf-ndc-london-2024-tickets-753697388177
#   # Number price in local currency
#   price: 20
#   # Currency code. Used in meta.
#   currency: GBP

# Basic images used for every event. I typically use the same ones for a location
# every year. There are templates for creating these in
# `/assets/images/events/_template`
images:
  # Image used in meta. Will be shown in Twitter/Facebook when links are shared.
  share: /assets/events/london_2026/event-share.jpg
  # Vector event logo
  logo: /assets/events/london_2026/event-logo.svg
  # Background Image used in the top-of-page hero.
  background: /assets/events/london_2026/event-hero-bg.jpg

# Most events have a conference partner. This is to highlight them.
partner:
  name: NDC London
  url: https://ndclondon.com/
  # Specific dimensions required. This is also in the image template.
  logo: /assets/events/london_2024/partner-logo.png

# The venue where the event will be held. Comment it out until a contract is in
# place. All fields required.
venue:
  name: The Slaughtered Lamb
  address: 34-35 Great Sutton Street, London EC1V 0DX
  url: https://www.urbanpubsandbars.com/venues/slaughtered-lamb

# Speakers. Speaker details are kept separate from events so that they can be
# re-used between multiple events. Reference a speaker by slug (lowercase,
# firstname_lastname). Referenced speakers must have a speaker file to be
# rendered.

# The host of the show
host:
  dylan_beattie:
    bio: "“Mad Lad Sigma Chad”.\n\nAccording to YouTube."
    image: "/assets/images/speakers/2026/dylan_beattie.jpg"

# How many finalists can be voted for using the voting page
# https://pubconf.io/vote/?event=<eventName>&hash=<secret>
#finalist_count: 3

# Speaker object hash. Use the speaker slugs as the keys, alphabetically listed.
# Within each speaker are the event-specific details.
speakers:
    arthur_doler:
        talk: "The Bug"
    helvira_goma:
        talk: "Still in thought process, sorry"
    chris_simon:
         talk: "Tech Exec or Psychopath? (AI Edition)"
    ash_bzak:
        talk: They Think My UI's Messy
    jo_minney:
        talk: "I Would Push Anything To Prod"
    william_brander:
        talk: "It's DNS"
    damian_brady:
        talk: "Broken Builds"
        image: /assets/images/speakers/2026/damian_brady.jpg
        bio: "Large Language Model/Singer/Actor"
    # dennis_doomen:
    #     talk: The curious case of the undiscovered production system
    # dylan_beattie:
    #     bio: One-man flashmob.
    #     talk: The Bug Lebowski
    #     image: /assets/images/speakers/dylan_beattie-london24.jpg
    # dylan_beattie:
    #     bio: One-man flashmob.
    #     talk: The Bug Lebowski
    #     image: /assets/images/speakers/dylan_beattie-london24.jpg    # edward_thomson:
    #     bio: drunk git
    #     talk: A bug! But who’s to blame?
    #     image: /assets/images/speakers/edward_thomson-london24.jpg
    # eli_holderness:
    #     talk: Big Poppins
    #     place: finalist
    # hannes_lowette:
    #     talk: "PubConf: the truth uncovered"
    # jo_franchetti:
    #     talk: Stand up against "yak" Shaving
    #     bio: Crinigerous Coder
    #     image: /assets/images/speakers/jo_franchetti-london24.jpg
    # lemon:
    #     talk: ChatGPT is a Conspiracy of the Illuminati
    #     bio: Chief Technical Symbologist
    #     image: /assets/images/speakers/lemon-london24.jpg
    # rendle:
    #     talk: "CSI: Sherlock She Wrote"
    #     place: champion
    #michelle_mannering:
    #    bio: "Microsoft fan-girl"
    #    talk: "The Death of Technology: what really happened to Zune?"
    #    image: "/assets/images/speakers/michelle_mannering2.png"

# Supporters array for the event.
supporters:
    # TrackJS is a required supporter.
  - name: TrackJS
    # Levels are "topshelf" and "rail" indicating if their are first-tier or
    # second-tier supporters.
    level: topshelf
    url: https://trackjs.com/
    image: /assets/images/supporters/tjs.webp
    # TrackJS is a required supporter.
  - name: Request Metrics
    # Levels are "topshelf" and "rail" indicating if their are first-tier or
    # second-tier supporters.
    level: topshelf
    url: https://requestmetrics.com/
    image: /assets/images/supporters/rm3.webp
---
## 18:00 Doors Open
Audience: Have a drink. Have a snack. Enjoy yourself.<br>
Speakers: Time to start panicking.

## 19:30 The Classic
20 slides. 15 seconds each. You know how this works.

## 20:30 The Linebreakers
The Linebreakers take the stage with all your favourite tech hits.

## 21:15 The PubConf Factor
You've seen The Linebreakers - now it's your turn.

## 22:00 The Linebreakers
The Linebreakers return the stage with all your favourite tech hits.

## 23:00 PubConf Karaoke
You were working as a waitress in cocktail bar...

## 01:00 Finish
Thank you, goodnight.

{% comment %}
Any markdown included here will be appended to the end of the "DETAILS" section.
{% endcomment %}
