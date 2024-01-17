---
# PubConf Events are defined by this markdown frontmatter. This template
# contains all the supported fields and descriptions.
#
layout: "event-2023"

# Full title of the event. Will be used in meta tags. Usually "PubConf City Year"
title: PubConf London 2024

# ISO8601 Date for the starting time of the event. Make sure the offset is in the
# event location timezone.
date: 2024-02-02T19:00:00Z

# ISO8601 Date for the ending time of the event.
end_date: 2024-02-02T23:00:00Z

# ISO8601 Date (without offset) for the local time of the event. This is used
# for display because dates are hard.
local_time: 2024-02-02T19:00

# Tickets object. Comment this out until tickets are ready to be sold.
tickets:
  # External URL to purchase tickets. Eventbrite, etc.
  url: https://www.eventbrite.co.uk/e/pubconf-ndc-london-2024-tickets-753697388177
  # Number price in local currency
  price: 20
  # Currency code. Used in meta.
  currency: GBP

# Basic images used for every event. I typically use the same ones for a location
# every year. There are templates for creating these in
# `/assets/images/events/_template`
images:
  # Image used in meta. Will be shown in Twitter/Facebook when links are shared.
  share: /assets/events/london_2024/event-share.jpg
  # Vector event logo
  logo: /assets/events/london_2024/event-logo.svg
  # Background Image used in the top-of-page hero.
  background: /assets/events/london_2024/event-hero-bg.jpg

# Most events have a conference partner. This is to highlight them.
partner:
  name: NDC London
  url: https://ndclondon.com/
  # Specific dimensions required. This is also in the image template.
  logo: /assets/events/london_2024/partner-logo.png

# The venue where the event will be held. Comment it out until a contract is in
# place. All fields required.
venue:
  name: The Barley Mow
  address: 104 Horseferry Road, Westminster, London, SW1P 2EE
  url: https://www.barleymowhorseferryrd.co.uk/

# Speakers. Speaker details are kept separate from events so that they can be
# re-used between multiple events. Reference a speaker by slug (lowercase,
# firstname_lastname). Referenced speakers must have a speaker file to be
# rendered.

# The host of the show
host:
  todd_gardner:
    bio: "Connoisseur of fine JavaScript"
    image: "/assets/images/speakers/todd_gardner_2.jpg"

# How many finalists can be voted for using the voting page
# https://pubconf.io/vote/?event=<eventName>&hash=<secret>
#finalist_count: 3

# Speaker object hash. Use the speaker slugs as the keys, alphabetically listed.
# Within each speaker are the event-specific details.
speakers:
    brandon_minnick:
        bio: "Tired of the bullshit"
        talk: "Whodunit: Solving the Open Source Murderer"
    dennis_doomen:
    dylan_beattie:
    eli_holderness:
    hannes_lowette:
    jo_franchetti:
    lemon:
        talk: ChatGPT is a Conspiracy of the Illuminati
        bio: Chief Technical Symbologist
        image: /assets/images/speakers/lemon-london24.jpg
    mark_rendle:
    michelle_mannering:
        bio: "Microsoft fan-girl"
        talk: "The Death of Technology: what really happened to Zune?"
        image: "/assets/images/speakers/michelle_mannering2.png"

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

{% comment %}
Any markdown included here will be appended to the end of the "DETAILS" section.
{% endcomment %}
