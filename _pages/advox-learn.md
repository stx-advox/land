---
title: "AdvoxLEARN"
layout: single
feature_row:
  - image_path: assets/images/beaturtle.png
    alt: "placeholder image 1"
    title: "Turtle"
    
  - image_path: /assets/images/LushanWolf.png
    alt: "placeholder image 2"
    title: "Wolf"
    
  - image_path: /assets/images/IsaBear.png
    title: "Bear"
permalink: /advoxlearn/    
toc: true
---
{% include feature_row %}

## Advox Clan System

### Turtle:

**Commons Loop Closing**

We can think of the Turtle clan as master architects & engineers that hold the blueprints …but in this case the house is on a planetary scale. Key characteristics or functions of Turtles in a system are **_observation & validation_**.

  

Whether in formal decision making or informal organization, Turtles are the ones who observe deliberation between Wolf and Bear and validate whether protocols were followed. In an informal interaction, for example, the Turtle will be the quiet one during a dialogue, waiting until the end to weigh the dialogue against the core values of the system.

  

One step removed from direct facilitation of the other clans, and with a keen engineering eye, Turtles make for the ideal trackers of closed loops of values. So Turtles are tracking the dialogue and sense-making between clans to ensure integrity of the system, to ensure value is circulated to where generators of that value work and live, and to ensure that there is no pure extraction in the system design.

  

So this speaks to the sometimes abstract closed loops of governance protocols or community value circulation. It also includes the tangible closed loops needed in ecological sustainability the world over. Ensuring long term Commons sustainability of many variations is built right into our Stacks Advocates system. Turtles validate that these variations are aligned with core values.

  

### Wolf:

**Commons Accessibility**

Wolf clan can be thought of as initiators, the constantly moving facilitators of Commons accessibility. The sparks for deliberation of important issues or actions; the guides for empowered paths of information dissemination. Key function being **_to gather the minds and voices of generators of value in consensus_**.

  

In formal decision making protocols it is a Wolf clan representative who initiates processes; bringing issues to the floor. Deliberation, if at all needed, happens between Wolf & Bear clans while the Turtle clan observes before validation or further deliberation. Wolf clan’s informal social organization function revolves around providing direct access to Commons to anybody interested. Whether the Commons of empowered bottom up consensus decision making or the Commons of innovation and value(s) circulation in the Stacks Advocates ecosystem. This empowered accessibility functions as a regenerating catalyst to push ecosystems forward.

  

### Bear:

**Commons Evolution**

Bear clan is simple, just think of it as effective medicine. Then think of medicine in all its possible forms; even the function of good friendship or guidance. Bears are the masters of transformative potential and effective transition. Key for our Stacks ecosystem, focused on OSS in Can’t Be Evil design & engineering, for a user-empowered internet. Transformation away from conventional models is fundamental for folks coming into our ecosystem, but just as important for our system too.

  

The Bear clan’s key functions are **_ensuring the growth or evolution of complex systems are healthy_**. Bears are responsible for the bridgework away from harmful structures… but they are also responsible for ensuring we don’t move too hastily into paradigm-shifting innovation. Bears are the medicine necessary for slowing down the process of change while doing due diligence to harvest and repurpose institutional leftovers on the careful terms of the community.

  

### The recursion of Turtle, Wolf, & Bear

Turtle is first in the ordered sequence, with all the elements of Wolf & Bear therein. Wolf & Bear are twins. Wolf coming before Bear in the sequence. This hints at a dynamic use of the three tiered system design rather than static. All three clans have a kind of  “memory” of one another, to be executed when needed in formal or informal social organization. Although one may be Turtle clan officially, in a given interaction, they may be best suited to assume their Wolf or Bear functions too.



### Turtle, Wolf, & Bear: Relationship, Governance, & Sustainability
**Background:**

Important to our governance & bottom up organization efforts is our direct dialogue with a historical indigenous council, The Kanienke'ha'ka (Mohawk) of The Five Nations Longhouse Confederacy. Early settler colonists were exposed to their matrilineal protocols of organization, which catalyzed modern concepts and language of Democratic values, Federalism, three branches of government & much more.

We have rare access to these protocols in pre-colonial form. We realize there was an entire culture of checks & balances omitted from our modern systems of social organization & representation, precisely due to lack of peaceful dialogue with Native nations.

Turtle, Wolf & Bear are our first steps on a path to a decolonized dialogue that can enable authentic alternatives to conventional governance, which is often easier said than actually achieved. TWB is the three tiered clan system of the Kanienke'ha'ka, which for millennia carved empowered paths of bottom up representation for entire Native nations. Speaking to deep cosmological functions of organization, the protocols are designed to maximize modularity for any collective of autonomous organizations.

Even though not all of us are interested in governance, accessible structures designed for empowered voices & representation are fundamental to fair power distribution. With TWB tapping into deep functions of the STX ecosystem, we can leverage autonomous organization well beyond just governance benefits & into blockchain innovation sustainability. Bottom up power here includes built-in structures for innovation decoupled from top down, value alienating control.

As STX advocates, we recognize this as a historical chance to achieve distributed power in blockchain based systems. An important means for long term sustainability in blockchain systems. Hope you are as excited as we are to learn and build together in this indigenous dialogue for sustainable protocols of organization.

## Dida-thing Clan reactions

To move over any existing content you'll want to copy the contents of your `_posts` folder to the new site. Along with any pages, collections, data files, images, or other assets you may have.

Next you'll need to convert posts and pages to use the proper layouts and settings. In most cases you simply need to update `_config.yml` to your liking and set the correct `layout` in their YAML Front Matter.

[**Front Matter defaults**](https://jekyllrb.com/docs/configuration/#front-matter-defaults) are your friend and I encourage you to leverage them instead of setting a layout and other global options in each post/page's YAML Front Matter.

Posts can be configured to use the `single` layout --- with reading time, comments, social sharing links, and related posts enabled. Adding the following to `_config.yml` will set these defaults for all posts:

```yaml
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      read_time: true
      comments: true
      share: true
      related: true
```

**Post/Page Settings**: Be sure to read through the "Working with..." documentation to learn about all the options available to you. The theme has been designed to be flexible --- with numerous settings for each.
{: .notice--info}

## Install dependencies

If this is your first time using Jekyll be sure to read through the [official documentation](https://jekyllrb.com/docs/home/) before jumping in. This guide assumes you have Ruby v2 installed and a basic understanding of how Jekyll works.

To keep your sanity and better manage dependencies I strongly urge you to [install Bundler](http://bundler.io/) with `gem install bundler` and use the following `Gemfile`:

```ruby
source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# gem "github-pages", group: :jekyll_plugins

# To upgrade, run `bundle update`.

gem "jekyll"
gem "minimal-mistakes-jekyll"

# The following plugins are automatically loaded by the theme-gem:
#   gem "jekyll-paginate"
#   gem "jekyll-sitemap"
#   gem "jekyll-gist"
#   gem "jekyll-feed"
#   gem "jekyll-include-cache"
#
# If you have any other plugins, put them here!
# Cf. https://jekyllrb.com/docs/plugins/installation/
group :jekyll_plugins do
end
```
### Clan Governance 

**ProTip:** To be bleeding edge install the latest (unreleased) version of Minimal Mistakes by adding this line to your `Gemfile`: `gem "minimal-mistakes-jekyll", :github => "mmistakes/minimal-mistakes"`.
{: .notice--info}

## Tools

To maintain a local Jekyll environment in sync with GitHub Pages replace the `gem "jekyll"` line with `gem "github-pages", group: :jekyll_plugins` and run the following:

```bash
$ bundle install
```

**Note:** The [GitHub Pages gem](https://github.com/github/pages-gem) installs additional dependencies that may need to be added to your `Gemfile` if you decide to remove the `gem "github-pages"` eg. `jekyll-paginate`, `jekyll-sitemap`, `jekyll-feed`, `jekyll-include-cache`, etc.
{: .notice--warning}
## Distributed Power Model
<figure>
  <img src="{{ '/assets/images/mm-bundle-install.gif' | relative_url }}" alt="bundle install in Terminal window">
</figure>

Depending on what gems you already have installed you may have to run `bundle update` to clear up any dependency issues. Bundler is usually pretty good at letting you know what gems need updating or have issues installing, to further investigate.

When using Bundler to manage gems you'll want to run Jekyll using `bundle exec jekyll serve` and `bundle exec jekyll build`.

Doing so executes the gem versions specified in `Gemfile.lock`. Sure you can test your luck with a naked `jekyll serve`, but I wouldn't suggest it. A lot of Jekyll errors originate from outdated or conflicting gems fighting with each other. So do yourself a favor and just use Bundler.
### Clan based Advox Grants Support
