---
layout: post
title: Solar navigation with an analog watch
author: Jeremy Reeder
date: 2020-09-09
tags: compass watch sundial
redirect_from:
  - /watch-navigation
  - /reverse-sundial
---

TL;DR -- A Russian-style 24-hour watch, aligned with the equatorial plane,
makes a fantastic solar compass.
{:.tangent .indent}

You probably already know some basic solar navigation:
- The sun rises in the east and sets in the west.
- The sun is directly south at noon.

But these are only rough approximations of the truth. And they can be plenty
misleading, so let's just call them LIES. Here I present _actual_ truths about
the position of the sun and a sometimes better way to find directions. No
equipment necessary except an analog watch.

### Lie #1: The sun rises in the east and sets in the west.

At my home near the 43<sup>rd</sup> parallel, trusting that the sun rises in
the east can mislead a fella by up to 34° in winter and summer. It's even less
accurate at higher latitudes. Here's the truth:

The sun rises approximately in the east and sets approximately in the west.
Twice a year, at the equinoxes, any deviation from due east and due west is
negligible.  But the sun deviates northward in both rising and setting as we
approach the June solstice.  And it deviates southward as we approach the
December solstice.  At each solstice you'll get at least 25° of deviation,
depending on your latitude.  Inside the polar circles, the sun won't actually
rise or set at all, it'll only circle around you just above or below the
horizon.
{:.indent}

### Lie #2: The sun is directly south at noon.

Yeah, okay, but when is noon? Do you trust the government to tell you? They may
mislead you by an hour or two. Local solar noon may not come at 12:00 civil
time. It varies with your longitudinal position within the time zone, and
daylight saving time moves it an hour clockwise. Today my solar noon is at
13:42.

Don't forget, of course, that in parts of the world the sun is _north_ at solar
noon. And in the tropics, it alternates.

## How 'bout a reverse sundial?

The hour hand of a 24-hour analog watch follows the apparent path of the sun,
so it comes in pretty handy as a compass. With a little trickery, even a
12-hour watch will do.

First you'll have to identify your local solar noon. Calculate it or look it
up. Use 12:00 as a rough approximation if you must, or 13:00 during daylight
saving time.

Next, let's use your watch as an equatorial sundial and align it with the
current time to find the north-south line. Whereas sundials are usually aligned
with the north-south line and then used to determine the current time, they
work equally well in reverse.

Read on to find out how to navigate with an analog watch.
{:.tangent}

### Navigating with a 24-hour dial

Navigation is easiest with daytime at the top of the dial and nighttime at the
bottom, as is common in Russian military watches. This arrangement generally
allows you to navigate without removing the watch from your wrist.

<div class="gallery" markdown="1">
![][russian-watch-photo]
*Raketa Sputnik -- a 24-hour watch from St Petersburg*
{:.indent}
</div>

#### (when north of the sun's path)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, with the solar noon position at the top.
2. Rotate your body till the hour hand points directly at the sun.<sup>2</sup>
3. The dial's solar noon position now points southward.

<sup>1</sup> Start vertical and tilt the dial away from you by an angle equal
to your latitude.
{:.tangent .indent}

<sup>2</sup> When the sun is north of the equator, you can use a knife blade to
cast a shadow on the hour hand. So you can aim your watch accurately without
looking at the sun.
{:.tangent .indent}

#### (when south of the sun's path)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, with the hour hand at the top.
2. Rotate your body till the solar noon position points directly at the sun.<sup>2</sup>
3. The hour hand now points southward.

<sup>1</sup> Start vertical and tilt the dial away from you by an angle equal
to your latitude.
{:.tangent .indent}

<sup>2</sup> When the sun is south of the equator, you can use a knife blade to
cast a shadow on the solar-noon position. So you can aim your watch accurately
without looking at the sun.
{:.tangent .indent}

### Navigating with a 12-hour dial

Remember, it's easier with a 24-hour dial. If you dislike bisecting angles or need an excuse to go watch-shopping, keep that in mind.
{:.tangent}

#### (when north of the sun's path)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, with the solar noon position at the top.
2. Rotate your body till the sun is halfway between the hour hand and solar noon.<sup>2</sup>
3. The dial's solar noon position now points southward.

<sup>1</sup> Start vertical and tilt the dial away from you by an angle equal
to your latitude.
{:.tangent .indent}

<sup>2</sup> When the sun is north of the equator, you can use a knife blade to
cast a shadow on the hour hand. So you can aim your watch accurately without
looking at the sun.
{:.tangent .indent}

#### (when south of the sun's path)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, and rotate it so that the position halfway between the hour hand and solar noon is at the top.
2. Rotate your body till the solar-noon position points directly at the sun.<sup>2</sup>
3. The top of the dial now points northward.

<sup>1</sup> Start vertical and tilt the dial away from you by an angle equal
to your latitude.
{:.tangent .indent}

<sup>2</sup> When the sun is south of the equator, you can use a knife blade to
cast a shadow on the solar-noon position. So you can aim your watch accurately
without looking at the sun.
{:.tangent .indent}

### How accurate is watch-based navigation?

The accuracy of this _reverse equatorial sundial_ depends primarily on your
identification of local solar noon and the alignment of your watch dial with
the equatorial plane.

#### Solar noon error

Using civil noon rather than solar noon can introduce up to 12° of
error<sup>*</sup>. You can blame Earth's elliptic orbit for a third of that.
The rest comes from your longitudinal distance from the center of your
time zone.

<sup>*</sup> Make that 27° if you forget to compensate for daylight saving
time.
{:.tangent}

#### Equatorial-alignment error

Holding your watch horizontally<sup>*</sup> like an amateur can add up to 45°
of error at the equator (or 17° in southern Idaho). This error peaks westward
at 09:00 and eastward at 15:00 solar time. But if you can hold it within 10° of
correct equatorial alignment, a goal easily met by eyeball, then your
misalignment-induced error shrinks to just 3° at its peaks.

<sup>*</sup> Most instruction on this topic assumes that the equally spaced
marks on a watch dial are suitable for a horizontal sundial. I'm right and
they're wrong.
{:.tangent}

### Where to, then?

Although useful anywhere with sun, watch-based navigation is _particularly_
well suited for a summertime polar expedition. The sun is up all day, the
equatorial plane is conveniently near horizontal, and the sun is on the right
side of it to cast a knife-blade shadow on your dial. Handy, since magnetic compasses are
[useless][compass-failure] inside the polar circles.


[russian-watch-photo]: {{ '/images/raketa-sputnik-watch.jpg' | prepend: site.url }}

[compass-failure]: https://cultofsea.com/general/using-magnetic-compass-in-polar-regions/
