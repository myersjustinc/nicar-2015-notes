# Sensor journalism: buzz or BS? #

**Speakers:**

* Amy Schmitz Weiss, San Diego State University
* John Keefe, WNYC
* Matt Waite, University of Nebraska
* Travis Hartman, University of Missouri

## Cicada tracker ##

Every 17 years, this brood of cicadas comes out of the ground--not breaking
news by any means. In 2013, WNYC reported on how you can predict their
emergence by the date the soil at a certain depth reaches a certain
temperature--so they distributed a tutorial to build Arduino-based temperature
sensors.

**800** locations got measured and reported back to the WNYC website, with a
total of 4,500 cicada sighting reports.

Led to a lot of coverage, including a sensor journalism conference at Columbia
University and a session at ONA!

John's message back then: "This isn't really journalism, but you guys should
really do this!" (His justification: This is more of a cool feature story.)

## Sleep tracker ##

John built a sensor in 2014 and strapped it to his arm to see whether he could
measure the quality of his sleep for a feature story about sleep.

They didn't distribute plans for this, but they still engaged with users to
track their sleep for a couple of months as part of that same feature story.

The tracking used a custom "sleep journal" built as a Web app and an iOS app.

**5,200** people submitted sleep records--a total of 63,700 records.

One-third of users submitted via the iOS application.

"Important discovery: Making apps is really hard. I do not recommend it."

## Bored and Brilliant ##

Someone asked John: "You can build apps, right? Can you build an app to track
how much people use their phones?"

Given the previous discovery, he answered "no", but apps already exist for the
major platforms to track this kind of thing--can we reach out to the companies
that publish these applications?

Moment app for iPhone added an opt-in feature to let users submit usage data to
WNYC!

"This is actually a sensor project...it's sensing whether your phone screen is
on."

## Luggage sensing ##

Or: How we turned a half-joke of a NICAR lighting talk into a sensor journalism project

In 2013, Matt Waite gave a lightning talk called "Soldering iron: Next great
data tool".

Built the TSA-a-tron: an accelerometer measuring the treatment of Matt's
luggage on the way to NICAR.

After this, he and Fergus Pitt designed a better luggage sensor with the
following requirements:

* Operating battery life of 24+ hours.

* High resolution, high-speed accelerometer responsiveness for recording brief
  impacts and movements.

* The ability to sense movement in any direction.

* A real-time clock for time-stamping every recorded accelerometer reading.

* An easy way for travelers to submit this data back to them.

Things they wrestled with:

* It was going to take weeks to create a prototype.

* Estimated unit cost: $100.

* "Wouldn't it be easier to take a cheap Android phone and write some
  software?"

  Depends on volume, honestly.

  But this was an experiment, so "we're gonna do it, economics be damned."

Built five units. Deployed four. One produced no usable data. One never turned
on. Two produced useful data.

Interestingly, "not one airport security officer in four countries said
anything about it." And the prototype was breadboarded in a soap dish--not
particularly clean-looking.

The two working units traveled 25,000 miles and logged almost 600,000
observations, including on a 26-hour trip from Lincoln to Nairobi.

That trip included something that was on the order of a four-foot drop in
Lincoln. Note that doesn't mean it actually fell four feet--just experienced a
similar force.


