---
# PubConf Events are defined by this markdown frontmatter. This template
# contains all the supported fields and descriptions.
#
# For how these files are consumed, see the layout at
# `/_layouts/event-2019.html`

# Full title of the event. Will be used in meta tags. Usually "PubConf City Year"
title: PubConf Oslo 2016

# ISO8601 Date for the starting time of the event. Make sure the offset is in the
# event location timezone.
date: 2016-06-11T18:00:00+2:00

# ISO8601 Date for the ending time of the event.
end_date: 2016-06-11T23:00:00+2:00

# ISO8601 Date (without offset) for the local time of the event. This is used
# for display because dates are hard.
local_time: 2016-06-11T18:00

# Tickets object. Comment this out until tickets are ready to be sold.
# tickets:
#   # External URL to purchase tickets. Eventbrite, etc.
#   url: https://ti.to/dddperth/pubconf-perth/
#   # Number price in local currency
#   price: 65
#   # Currency code. Used in meta.
#   currency: AUD

# Basic images used for every event. I typically use the same ones for a location
# every year. There are templates for creating these in
# `/assets/images/events/_template`
images:
  # Image used in meta. Will be shown in Twitter/Facebook when links are shared.
  share: /assets/images/events/oslo/event-share.jpg
  # Vector event logo
  logo: /assets/images/events/oslo/event-logo.svg
  # Background Image used in the top-of-page hero.
  background: /assets/images/events/oslo/event-hero-bg.jpg

# Most events have a conference partner. This is to highlight them.
partner:
  name: NDC Oslo
  url: https://ndcoslo.com
  # Specific dimensions required. This is also in the image template.
  logo: /assets/images/events/oslo/partner-logo.png

# The venue where the event will be held. Comment it out until a contract is in
# place. All fields required.
venue:
  name: The Scotsman
  address: Karl Johans Gate 17 0159 Oslo Norway
  url: https://scotsman.no/

# Speakers. Speaker details are kept separate from events so that they can be
# re-used between multiple events. Reference a speaker by slug (lowercase,
# firstname_lastname). Referenced speakers must have a speaker file to be
# rendered.

# The host of the show
host: todd_gardner

# How many finalists can be voted for using the voting page
# https://pubconf.io/vote/?event=<eventName>&hash=<secret>
finalist_count: 3

# Speaker object hash. Use the speaker slugs as the keys, alphabetically listed.
# Within each speaker are the event-specific details.
speakers:
  ben_cull:
    talk: "How to Brew Beer"
  david_neal:
    talk: "Win Hearts with Your Craptastic Drawings"
  dylan_beattie:
    talk: "So You Think Your Code Isn't Mission Critical?"
  einar_host:
    talk: "Pragmatism is Poison"
  evelina_gabasova:
    talk: "Welcoming our AI Overlords"
  jimmy_bogard:
    talk: "When You've Fucked Up"
  karlhenrik_nilsson:
    talk: "The Internet of Less-Useless Things"
  karoline_klever:
    talk: "The Miscommunicating Developer"
  lars_klint:
    talk: "The Day Kittens Took Over the World Using HoloLens"
  sebastien_lambla:
    talk: "How to Always Be Right on the Internets"
  stefan_daugaardpoulsen:
    talk: "IoT is Misspelled IoU"
  troy_hunt:
    talk: "Let's Face It--Security is Pointless"

# Supporters array for the event.
supporters:
    # TrackJS is a required supporter.
  - name: TrackJS
    # Levels are "topshelf" and "rail" indicating if their are first-tier or
    # second-tier supporters.
    level: topshelf
    url: https://trackjs.com/
    image: /assets/images/supporters/tjs.png
---

{% comment %}
Any markdown included here will be appended to the end of the "DETAILS" section.
{% endcomment %}
