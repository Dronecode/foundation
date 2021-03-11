# Dronecode Foundation / Google Season of Docs 2021

The [Dronecode Foundation](https://www.dronecode.org) is applying for the [2021 Google Season of Docs](https://developers.google.com/season-of-docs).

The [PX4 Autopilot](https://px4.io) is a fast-growing open-source community hosted by the [Dronecode Foundation]((https://www.dronecode.org)), supported by [many companies](https://www.dronecode.org/our-members/) that use it in production. While PX4 has been open source for quite some time, and we have been assigning vast resources into our documentation, we believe there are still areas where we could improve. You can read more about what we have accomplished in our [2020 annual contributor report](https://www.dronecode.org/contributor-report-2020-celebrating-one-big-year-of-open-source/).

We are looking for a skilled technical writer who can help with a few projects. We believe right now is a great time to get involved, as we have been working on focusing our efforts and are have been working on a documentation redesign. Just a couple of months ago, we launched our new and improved docs layout. ([docs.px4.io](https://docs.px4.io/master/))

Please reach out on the #documentation channel in the PX4 Autopilot Slack if you have any questions.

Here is a list of our proposals, as well as some resources to help you learn about GraphQL.

### 1. MAVLink networking (medium/hard)

**Make it really easy for developers getting started with PX4 to
understand the basics of MAVLink networking and the MAVLink interface**

There are constant questions on our community channels regarding how to connect multiple devices and how to deal with those. This one might be easy but super helpful.

**Expected outcomes:** A succint and easy to follow guide on how to
properly interface with MAVLink coming in and out from PX4, and how to
consume it from multiple sources, with a list of utilities that can be
leveraged to succeed. This guide should also contain examples of the
most common scenarios where you want to consume MAVLink from multiple
sources.
**Skills required/preferred:** APIs / Markdown / Basic Networking
**Mentor: Ramón Roche ([@mrpollo](https://github.com/mrpollo))**

### 2. Camera trigger (medium/hard)

**Make it very clear wht the current interfaces are for camera trigger,
and how to use them**

Our current "Camera Trigger" documentation clearly needs an update to separate out what you can do with the MAVLink camera vs directly connected to the flight controller.

**Expected outcomes:** Clean up our camera management documentation to
include best practices for both ways of interfacing with cameras, and
when to recommend which.
**Skills required/preferred:** APIs / Markdown / Python
**Mentor:**


### 3. Companion computers. (medium)

**Make it really easy for developers to choose from a list of compatible
companion computers to use on their drones**

We have a [very minimal document](https://docs.px4.io/master/en/peripherals/companion_computer_peripherals.html) on the basic concepts behind working with companion computers.

**Expected outcomes:** Create a turnkey solution document up to par in quality with the rest of the documentation, with recommendations on some of the currently supported and tested hardware, along with instructions on how to set them up, in both communication and power, as well as adding essential peripherals.
**Skills required/preferred:** Electronics / Markdown / Embedded
**Mentor:**

### 4. Mixers (hard)

**Explain how the Mixing and Actuator logic works within PX4**

The [current docs](https://docs.px4.io/master/en/concept/mixing.html) are hard to read, need to be updated with recent changes in the architecture, and revamped to get to a level were a developer could easily understand them and start contributing.

**Expected outcomes:** An updated and revamped mixing and actuator doc,
that is able to properly translate the complexity behidn the topic into
easy to follow steps.
**Skills required/preferred:** Control and Navigation / Embedded /
Markdown
**Mentor:**

### 5. Geometry files (medium/hard)
nothing on these in the docs.
**Expected outcomes:**
**Skills required/preferred:**
**Mentor:**

### 6. Gazebo Simulations (easy/medium)
better docs on customisation.
**Expected outcomes:**
**Skills required/preferred:**
**Mentor:**

---

## Submitting Documentation Proposals (for prospective mentors)

If you would like to submit a proposal for an initiative that you would like to mentor, feel free to open a PR to add another section to this document above.

```md
# My Example Initiative

> **Status:**
> **You can begin researching and submitting for this PR now**

<description>

**Expected outcomes:**

**Skills required/preferred:**

**Mentor:** your name and github account

**Related Issues:**
```

---

## Resources

### Official PX4 Documentation

- PX4 Documentation: [https://docs.px4.io/master/](https://docs.px4.io/master/)
- PX4 Site: [https://px4.io](https://px4.io)

### Recommended Links

- [PX4 Developer Summit 2019](https://www.dronecode.org/dev-summit-zurich/)
- [PX4 Developer Summit 2020](https://px4.io/virtual-2020/)
- [Highlights from the 2020 PX4 Developer Summit](https://www.dronecode.org/highlights-from-the-2020-px4-developer-summit/)
- [PX4 Autopiot YouTube Channel](https://www.youtube.com/channel/UCkrtSvera-xusjMtgMUe-HA)
