---
# PubConf Events are defined by this markdown frontmatter. This template
# contains all the supported fields and descriptions.
#
layout: "event-2023"

# Full title of the event. Will be used in meta tags. Usually "PubConf City Year"
title: PubConf Atlanta 2024

# ISO8601 Date for the starting time of the event. Make sure the offset is in the
# event location timezone.
date: 2024-06-13T19:00:00-04:00

# ISO8601 Date for the ending time of the event.
end_date: 2024-06-13T22:00:00-04:00

# ISO8601 Date (without offset) for the local time of the event. This is used
# for display because dates are hard.
local_time: 2024-06-13T19:00

# Tickets object. Comment this out until tickets are ready to be sold.
#tickets:
  # External URL to purchase tickets. Eventbrite, etc.
  #url: https://www.eventbrite.com/e/pubconf-kansas-city-2023-tickets-634291331447
  # Number price in local currency
  #price: 40
  # Currency code. Used in meta.
  #currency: USD

# Basic images used for every event. I typically use the same ones for a location
# every year. There are templates for creating these in
# `/assets/images/events/_template`
images:
  # Image used in meta. Will be shown in Twitter/Facebook when links are shared.
  share: /assets/events/atlanta_2024/event-share.jpg
  # Vector event logo
  logo: /assets/events/atlanta_2024/event-logo.svg
  # Background Image used in the top-of-page hero.
  background: /assets/events/atlanta_2024/event-hero-bg.jpg

tagline: "PubConf Goes Wild Wild West"

# Most events have a conference partner. This is to highlight them.
partner:
  name: RenderATL
  url: https://www.renderatl.com/
  # Specific dimensions required. This is also in the image template.
  logo: /assets/events/atlanta_2024/partner-logo.png

# The venue where the event will be held. Comment it out until a contract is in
# place. All fields required.
#venue:
  #name: Howl at the Moon
  #address: 1334 Grand Blvd. Kansas City, MO 64106
  #url: https://www.howlatthemoon.com/kansas-city/

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



# Supporters array for the event.
supporters:
  - name: Request Metrics
    # Levels are "topshelf" and "rail" indicating if their are first-tier or
    # second-tier supporters.
    level: topshelf
    url: https://requestmetrics.com/
    image: /assets/images/supporters/rm3.webp
# TrackJS is a required supporter.
  - name: TrackJS
    # Levels are "topshelf" and "rail" indicating if their are first-tier or
    # second-tier supporters.
    level: topshelf
    url: https://trackjs.com/
    image: /assets/images/supporters/tjs.webp
    # TrackJS is a required supporter.

---

{% comment %}
Any markdown included here will be appended to the end of the "DETAILS" section.
{% endcomment %}