---
# PubConf Events are defined by this markdown frontmatter. This template
# contains all the supported fields and descriptions.
#
layout: "event-2023"

# Full title of the event. Will be used in meta tags. Usually "PubConf City Year"
title: PubConf Minneapolis 2022

# ISO8601 Date for the starting time of the event. Make sure the offset is in the
# event location timezone.
date: 2022-11-17T19:00:00-6:00

# ISO8601 Date for the ending time of the event.
end_date: 2022-11-17T23:00:00-6:00

# ISO8601 Date (without offset) for the local time of the event. This is used
# for display because dates are hard.
local_time: 2022-11-17T19:00

# Tickets object. Comment this out until tickets are ready to be sold.
tickets:
  # External URL to purchase tickets. Eventbrite, etc.
  url: https://events.eventzilla.net/e/pubconf-minneapolis-2022-2138574280
  # Number price in local currency
  price: 40
  # Currency code. Used in meta.
  currency: USD

# Basic images used for every event. I typically use the same ones for a location
# every year. There are templates for creating these in
# `/assets/images/events/_template`
images:
  # Image used in meta. Will be shown in Twitter/Facebook when links are shared.
  share: /assets/events/minneapolis_2023/event-share.jpg
  # Vector event logo
  logo: /assets/events/minneapolis_2023/event-logo.svg
  # Background Image used in the top-of-page hero.
  background: /assets/events/minneapolis_2023/The_Hell.webp

# Most events have a conference partner. This is to highlight them.
partner:
  name: NDC Minnesota
  url: https://ndcminnesota.com/
  # Specific dimensions required. This is also in the image template.
  logo: /assets/events/minneapolis_2023/partner-logo.png

# The venue where the event will be held. Comment it out until a contract is in
# place. All fields required.
venue:
  name: The Devil's Advocate
  address: 1070 Nicollet Mall, Minneapolis, MN 55403
  url: https://devilsadvocatemn.com/

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
    talk: "Don’t Read The Comments"
  carl_franklin:
    talk: "My Struggles with Vocal Dyslexia"
    place: champion
  dan_lew:
    talk: "Web's Inferno"
    bio: "Wait, is this thing recording?"
    image: "/assets/images/speakers/dan_lew_2.jpg"
  donnie_berkholz:
    talk: "Dante's Inferno of Feature Requests"
    bio: "Head of the Asylum"
    image: "/assets/images/speakers/donnie_berkholz_2.jpg"
  heidi_waterhouse:
    talk: "Hell is Empty - Succession Planning"
  kat_t:
    talk: "Crypto2020JS - Encryption For TLA Compliance"
  hannes_lowette:
    talk: "Bullshit Champion Round"
  laura_bell:
    talk: "Bullshit Champion Round"
  lemon:
    talk: "Bullshit Champion Round"
    place: "champion"

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
