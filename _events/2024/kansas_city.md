---
# PubConf Events are defined by this markdown frontmatter. This template
# contains all the supported fields and descriptions.
#
layout: "event-2024"

# Full title of the event. Will be used in meta tags. Usually "PubConf City Year"
title: PubConf Kansas City 2024
excerpt: Rapid-fire funny talks, musical acts, and comedy stunts from amazing developers. At the pub.

# ISO8601 Date for the starting time of the event. Make sure the offset is in the
# event location timezone.
date: 2024-06-28T19:00:00-04:00

# ISO8601 Date for the ending time of the event.
end_date: 2024-06-28T23:30:00-04:00

# ISO8601 Date (without offset) for the local time of the event. This is used
# for display because dates are hard.
local_time: 2024-06-28T19:00

# Tickets object. Comment this out until tickets are ready to be sold.
tickets:
  # External URL to purchase tickets.
  url: https://ti.to/kansas-city-developers-conference/pubconf-kc-2024
  # Number price in local currency
  price: 30
  # Currency code. Used in meta.
  currency: USD

# Basic images used for every event. I typically use the same ones for a location
# every year. There are templates for creating these in
# `/assets/images/events/_template`
images:
  # Image used in meta. Will be shown in Twitter/Facebook when links are shared.
  share: /assets/events/kc_2024/event-share-3.jpg
  share_width: 1200
  share_height: 630

  # Vector event logo
  logo: /assets/events/kc_2024/event-logo-2.svg
  # Background Image used in the top-of-page hero.
  background: /assets/events/kc_2024/event-hero-bg2.jpg

tagline: "ERROR: theFuture is undefined"

# Most events have a conference partner. This is to highlight them.
partner:
  name: KCDC
  url: https://www.kcdc.info/
  # Specific dimensions required. This is also in the image template.
  logo: /assets/events/kansas_city_2023/partner-logo.png

# The venue where the event will be held. Comment it out until a contract is in
# place. All fields required.
venue:
  name: Nighthawk
  address: 1228 Baltimore Ave, Kansas City, MO 64105
  url: https://www.nighthawkkc.com

# Speakers. Speaker details are kept separate from events so that they can be
# re-used between multiple events. Reference a speaker by slug (lowercase,
# firstname_lastname). Referenced speakers must have a speaker file to be
# rendered.

# The host of the show
host:
  lemon:
    bio: Just sitting around here waiting for the future to start.
    image: "/assets/images/speakers/lemon_headinhands.webp"

# How many finalists can be voted for using the voting page
# https://pubconf.io/vote/?event=<eventName>&hash=<secret>
#finalist_count: 3

# Speaker object hash. Use the speaker slugs as the keys, alphabetically listed.
# Within each speaker are the event-specific details.
speakers:
  sarah_young:
    #bio: Sarah's bio
    #talk: Sarah's talk
  #ash_bzak:
    #bio: Ash's bio
    #talk: According to TNG, it's less than 20 years to World War III
  brandon_minnick:
    #bio: Brandon's bio
    talk: Humanity Achieves Peak Laziness
  jennifer_wadella:
    bio: Your Boss, the Geriatric Millennial
    talk: The Day Millennials Manage the Technical Workforce
  eli_holderness:
    #bio: Eli's bio
    #talk: Eli's talk
  dan_neciu:
    #bio: Neciu's bio
    #talk: Neciu's talk
  glenn_henriksen:
    #bio: Glenn's bio
    talk: The Future Is Reduced For Quick Sale
  gabby_spurling:
    #bio: Gabby's bio
    #talk: Gabby's talk
  eldert_grootenboer:
    bio: Herder of Cats
    talk: Program Managers Against Humanity
  darcy_lussier:
    #bio: D'arcy's bio
    #talk: D'arcy's talk

# Supporters array for the event.
supporters:
  # TrackJS is a required supporter.
  - name: TrackJS
    # Levels are "topshelf" and "rail" indicating if their are first-tier or
    # second-tier supporters.
    level: topshelf
    url: https://trackjs.com/
    image: /assets/images/supporters/tjs.webp
  # Savas Labs is a top shelf sponsor for PubConf KC
  - name: Savas Labs
    level: topshelf
    url: https://savaslabs.com/
    image: /assets/images/supporters/savas-labs.svg

---

{% comment %}
Any markdown included here will be appended to the end of the "DETAILS" section.
{% endcomment %}