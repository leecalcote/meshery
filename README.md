# <a href="https://layer5.io/meshery"><img align="left" src="https://layer5.io/assets/images/meshery/Meshery-RGB-Full-Light.png"  width="25%" /></a>

[![Docker Pulls](https://img.shields.io/docker/pulls/layer5/meshery.svg)](https://hub.docker.com/r/layer5/meshery)
[![Go Report Card](https://goreportcard.com/badge/github.com/layer5io/meshery)](https://goreportcard.com/report/github.com/layer5io/meshery)
[![Build Status](https://github.com/layer5io/meshery/workflows/Meshery/badge.svg)](https://github.com/layer5io/meshery/actions)
[![GitHub](https://img.shields.io/github/license/layer5io/meshery.svg)](LICENSE)
[![GitHub issues by-label](https://img.shields.io/github/issues/layer5io/meshery/help%20wanted.svg)](https://github.com/layer5io/meshery/issues?q=is%3Aopen+is%3Aissue+label%3A"help+wanted")
[![Website](https://img.shields.io/website/https/layer5.io/meshery.svg)](https://layer5.io/meshery/)
[![Twitter Follow](https://img.shields.io/twitter/follow/layer5.svg?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=mesheryio)
[![Slack](http://slack.layer5.io/badge.svg)](http://slack.layer5.io)

A multi-mesh management plane with initial functionality as a playground to faciliate learning about functionality and performance of different service meshes. [Meshery](https://layer5.io/meshery) also serves as a service mesh performance benchmark.
  
In an effort to produce service mesh agnostic tooling, Meshery uses a [common performance benchmark specification](https://github.com/layer5io/service-mesh-benchmark-spec) to capture and share environment information and test configuration. As a Service Mesh Interface (SMI) partner, Meshery participates in advancing service mesh adoption through standardization of APIs.
 
## <a name="functionality">Functionality</a>
<img align="right" src="https://github.com/layer5io/meshery/raw/master/ui/static/img/dashboard-screenshot.png" alt="Service Mesh Playground" width="50%" />

### Multi-mesh Performance Benchmark

Meshery is intended to be a vendor and project-neutral utility for uniformly benchmarking the performance of service meshes. Between service mesh and proxy projects (and surprisingly, [within a single project](https://layer5.io/landscape#tools)), a number of different tools *and results* exist. 

### Multi-mesh Functionality Playground

A service mesh playground to faciliate learning about functionality of different service meshes. Meshery incorporates a visual interface for manipulating traffic routing rules. Sample applications will be included in Meshery. 

## <a name="running">Running Meshery</a>

See the [project site](https://layer5.io/meshery) for quick start instructions and [project documentation](https://meshery.layer5.io/docs) for a complete set of Meshery documentation.

## Presentations
- [KubeCon EU 2019](https://kccnceu19.sched.com/event/MPf7/service-meshes-at-what-cost-lee-calcote-layer5-girish-ranganathan-solarwinds?iframe=no&w=100%&sidebar=yes&bg=no) | ([video](https://www.youtube.com/watch?v=LxP-yHrKL4M&list=PLYjO73_1efChX9NuRaU7WocTbgrfvCoPE), [deck](https://calcotestudios.com/talks/decks/slides-kubecon-eu-2019-service-meshes-at-what-cost.html))
- Istio Founders Meetup @ KubeCon EU 2019 | [deck](https://calcotestudios.com/talks/decks/slides-istio-meetup-kubecon-eu-2019-istio-at-scale-large-and-small.html)
- [Cloud Native Rejekts EU 2019](https://cfp.cloud-native.rejekts.io/cloud-native-rejekts-eu-2019/speaker/GZQTEM/) | [deck](https://calcotestudios.com/talks/decks/slides-cloud-native-rejekts-2019-evaluating-service-meshes.html)
- [DockerCon 2019 Open Source Summit](https://dockercon19.smarteventscloud.com/connect/sessionDetail.ww?SESSION_ID=309149&tclass=popup#.XJxH-TOcbjI.twitter) | [deck](https://calcotestudios.com/talks/decks/slides-dockercon-2019-establishing-an-open-source-office.html), [video](https://www.docker.com/dockercon/2019-videos?watch=open-source-summit-service-mesh)
- [Container World 2019](https://tmt.knect365.com/container-world/speakers/lee-calcote) | [deck](https://calcotestudios.com/talks/decks/slides-container-world-2019-service-meshes-but-at-what-cost.html)
- [Service Mesh Day](https://servicemeshday.com/schedule/) | [deck](https://docs.google.com/presentation/d/1T0w5sXiUYtjHhmwJYF7VI-q5lgYAN46-Yn8ey0EZV-A/edit?usp=sharing), [video](https://youtu.be/CFj1O_uyhhs)
- [Innotech San Antonio](https://innotechsanantonio2019.sched.com/event/Lmlb/the-enterprise-path-to-service-mesh-architectures?iframe=no&w=100%&sidebar=yes&bg=no) | [deck](https://calcotestudios.com/talks/decks/slides-innotech-san-antonio-2019-the-enterprise-path-to-service-mesh.html)
- [CNCF Networking WG](https://github.com/cncf/wg-networking) | [deck](https://www.slideshare.net/leecalcote/benchmarking-service-meshes-cncf-networking-wg-141938576), [video](https://www.youtube.com/watch?v=2_JwCc-kLMA&list=PLYjO73_1efChX9NuRaU7WocTbgrfvCoPE)

<a name="contributing"></a><a name="community"></a>
## Community
<div>
This project is community-built and welcomes collaboration! See the <a href="https://docs.google.com/document/d/17OPtDE_rdnPQxmk2Kauhm3GwXF1R5dZ3Cj8qZLKdo5E/edit">Meshery Contributors Welcome Guide</a>. 
<p>
  <ul>
    <li style="list-style-type: circle;"><em><strong>Join</strong></em> <a href="https://drive.google.com/open?id=1c07UO9dS7_tFD-ClCWHIrEzRnzUJoFQ10EzfJTpS7FY">weekly community meeting</a> on <a href="https://calendar.google.com/calendar/b/1?cid=bGF5ZXI1LmlvX2VoMmFhOWRwZjFnNDBlbHZvYzc2MmpucGhzQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20">Fridays from 10am - 11am Central</a>.</li>
    <ul>
        <li><em><strong>Watch</strong></em> community <a href="https://www.youtube.com/playlist?list=PL3A-A6hPO2IMPPqVjuzgqNU5xwnFFn3n0">meeting recordings</a>.</li>
    </ul>
    <li style="list-style-type: circle;"><em><strong>Access</strong></em> the <a href="https://drive.google.com/drive/u/4/folders/0ABH8aabN4WAKUk9PVA">community drive</a>.</li>
      <ul>
        <li><em><strong>Comment</strong></em> on the <a href="https://drive.google.com/open?id=15Gv1kTP8QHaMrDadfmgVmmS3hQn6YKFVag38Cr_JBEI">design document.</a></li>
      </ul>
    </ul>
</p>
</div>

*Not sure where to start?* Grab an open issue with the [help-wanted label](../../labels/help%20wanted).

## More about Meshery
<table border="0"><tr><td width="50%">
- [Functionality](#functionality)
- [Running Meshery](#running)
  - [Quick start](https://layer5.io/meshery/#getting-started)
  - [Docs](https://meshery.layer5.io/docs)
  - [Community Drive](https://drive.google.com/drive/u/0/folders/0ABH8aabN4WAKUk9PVA) (Request access!)
    - [Architecture](https://drive.google.com/open?id=1SQMfyu5shjpGKlYONdVzOtd7UYTgLWBcgUvHMLCZ2tY)
- [Contributing](CONTRIBUTING.md/#contributing)
  - [Write an adapter](CONTRIBUTING.md/#adapter)
  - [Build the project](CONTRIBUTING.md/#building)</td><td align="center">
  <i>If you’re using Meshery or if you like the project, please ★ star this repository to show your support! 🤩</i>
<a href="../../stargazers"><img align="center" src="https://starchart.cc/layer5io/meshery.svg" width="400" height="400" /></a></td></tr></table>


### Stargazers
<p align="center">
  <i>If you’re using Meshery or if you like the project, please <a href="../../stargazers">★</a> star this repository to show your support! 🤩</i>
<a href="../../stargazers"><img align="center" src="https://starchart.cc/layer5io/meshery.svg" /></a></p>

<button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star leecalcote/meshery" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:219773201,&quot;client_id&quot;:&quot;2026749041.1564006892&quot;,&quot;originating_request_id&quot;:&quot;B734:4EA6:270D004:3DC9A17:5DC1C2B7&quot;,&quot;originating_url&quot;:&quot;https://github.com/leecalcote/meshery/edit/master/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/leecalcote/meshery/blob/master/README.md&quot;,&quot;user_id&quot;:7570704}}" data-hydro-click-hmac="68139c98ba29ed43e7c48d63dde40a494f7a3d674cbd3849d0e77d4815bc1415" data-ga-click="Repository, click star button, action:blob#edit; text:Star">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"></path></svg>
        Star
</button>

## License

This repository and site are available as open source under the terms of the [Apache 2.0 License](https://opensource.org/licenses/Apache-2.0).

**About Layer5**

[Layer5.io](https://layer5.io) is a service mesh community, serving as a repository for information pertaining to the surrounding technology ecosystem (service meshes, api gateways, edge proxies, ingress and egress controllers) of microservice management in cloud native environments.

