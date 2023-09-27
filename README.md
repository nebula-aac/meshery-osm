> [!IMPORTANT]
> Open Service Mesh is an archived project. Consequently, the Meshery Adapter for OSM is an archived adapter.


<p style="text-align:center;" align="center"><a href="https://layer5.io/meshery"><picture align="center">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/meshery/meshery/master/.github/assets/images/meshery/meshery-logo-dark-text-side.svg"  width="70%" align="center" style="margin-bottom:20px;">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/meshery/meshery/master/.github/assets/images/meshery/meshery-logo-light-text-side.svg" width="70%" align="center" style="margin-bottom:20px;">
  <img alt="Shows an illustrated light mode meshery logo in light color mode and a dark mode meshery logo dark color mode." src="https://raw.githubusercontent.com/meshery/meshery/master/.github/assets/images/meshery/meshery-logo-tag-light-text-side.png" width="70%" align="center" style="margin-bottom:20px;">
</picture></a><br /><br /></p>
 
[![Docker Pulls](https://img.shields.io/docker/pulls/layer5/meshery-osm.svg)](https://hub.docker.com/r/layer5/meshery-osm)
[![Go Report Card](https://goreportcard.com/badge/github.com/layer5io/meshery-osm)](https://goreportcard.com/report/github.com/layer5io/meshery-osm)
[![Build Status](https://img.shields.io/github/actions/workflow/status/meshery/meshery-osm/multi-platform.yml?branch=master)](https://github.com/meshery/meshery-osm/actions)
[![GitHub](https://img.shields.io/github/license/layer5io/meshery-osm.svg)](LICENSE)
[![GitHub issues by-label](https://img.shields.io/github/issues/layer5io/meshery-osm/help%20wanted.svg)](https://github.com/layer5io/meshery-osm/issues?q=is%3Aopen+is%3Aissue+label%3A"help+wanted")
[![Website](https://img.shields.io/website/https/layer5.io/meshery.svg)](https://layer5.io/meshery/)
[![Twitter Follow](https://img.shields.io/twitter/follow/layer5.svg?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=mesheryio)
[![Slack](https://img.shields.io/badge/Slack-@layer5.svg?logo=slack)](http://slack.layer5.io)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/3564/badge)](https://bestpractices.coreinfrastructure.org/projects/3564)

<h1>Meshery Adapter for Open Service Mesh</h1>
<h2><a href="https://meshery.layer5.io/docs">Open Service Mesh</a></h2>
<a href="https://openservicemesh.io">
 <img src="https://raw.githubusercontent.com/layer5io/meshery-osm/master/img/readme/osm.svg" style="margin:10px;" width="125px" 
   alt="Open Service Mesh" align="left" />
</a>
<p>
<a href="https://openservicemesh.io">Open Service Mesh</a> (OSM) is a lightweight and extensible cloud native service mesh.
 <br /> <br /> <br /> <br /> <br /> 
</p>

<p style="clear:both;">
<h2><a href="https://layer5.io/meshery">Meshery</a></h2>
<a href="https://meshery.io"><picture><img src="./img/readme/meshery-logo-light-text.svg#gh-dark-mode-only"
style="margin:10px;" width="10%" 
alt="Meshery - the Cloud Native Manager" align="left" />
<img src="./img/readme/meshery-logo-dark-text.svg#gh-light-mode-only"
style="margin:10px;" width="10%" 
alt="Meshery - the Cloud Native Manager" align="left" /></picture></a>
As a self-service engineering platform, <a href="https://meshery.io">Meshery</a> enables collaborative design and operation of cloud native infrastructure. Through it's extension points, Meshery offers the ability to optionally plugin adapters in order to more deeply integrate with specific systems like Open Service Mesh.
<br /><br /><p align="center"><i>If you’re using Meshery or if you like the project, please <a href="https://github.com/layer5io/meshery/stargazers">★</a> star this repository to show your support! 🤩</i></p>
</p>

<p style="clear:both;">
<h2><a name="contributing"></a><a name="community"></a> <a href="https://slack.meshery.io">Community</a> and <a href="https://docs.meshery.io/project/contributing">Contributing</a></h2>
Our projects are community-built and welcome collaboration. 👍 Be sure to see the <a href="https://layer5.io/community/newcomers">Contributor Journey Map</a> for a tour of resources available to you and jump into our <a href="https://slack.meshery.io">Slack</a>! Contributors are expected to adhere to the <a href="https://github.com/cncf/foundation/blob/master/code-of-conduct.md">CNCF Code of Conduct</a>.

<a href="https://slack.meshery.io">

<picture align="right">
  <source media="(prefers-color-scheme: dark)" srcset="./img/readme/slack-dark-128.png"  width="110px" align="right" style="margin-left:10px;margin-top:10px;">
  <source media="(prefers-color-scheme: light)" srcset="./img/readme/slack-128.png" width="110px" align="right" style="margin-left:10px;padding-top:5px;">
  <img alt="Shows an illustrated light mode meshery logo in light color mode and a dark mode meshery logo dark color mode." src="/img/readme/slack-128.png" width="110px" align="right" style="margin-left:10px;padding-top:13px;">
</picture>
</a>

<p>
✔️ <em><strong>Join</strong></em> any or all of the weekly meetings on the <a href="https://meshery.io/calendar">community calendar</a>.<br />
✔️ <em><strong>Watch</strong></em> community <a href="https://www.youtube.com/channel/UCFL1af7_wdnhHXL1InzaMvA?sub_confirmation=1">meeting recordings</a>.<br />
✔️ <em><strong>To access the Community Drive</strong></em>, fill <a href="https://layer5.io/newcomer">Community Member Form</a>.<br />
✔️ <em><strong>Discuss</strong></em> in the <a href="https://discuss.layer5.io">Community Forum</a>.<br />
</p>
<p align="center">
<i>Not sure where to start?</i> Grab an open issue with the <a href="https://github.com/issues?q=is%3Aopen+is%3Aissue+archived%3Afalse+org%3Alayer5io+org%3Ameshery+org%3Aservice-mesh-performance+org%3Aservice-mesh-patterns+org%3Alayer5labs+label%3A%22help+wanted%22+">help-wanted label</a>.
</p>

**License**

This repository and site are available as open source under the terms of the [Apache 2.0 License](https://opensource.org/licenses/Apache-2.0).
