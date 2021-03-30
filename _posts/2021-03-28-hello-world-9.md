---
title: Hello World
categories: technology
subtitle: subtitle lorem ipsum dolor sit amet consectetur.
thumbnail: https://images.unsplash.com/photo-1498758536662-35b82cd15e29?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxzZWFyY2h8Mjd8fHdvcmtpbmd8ZW58MHx8MHw%3D&auto=format&fit=crop&w=800&q=60
---

In [this whitepaper](www.casca.ca/lrp2010/Docs/LRPReports/CAI.pdf) for the [CASCA 2010 Long Range Plan](http://www.casca.ca/lrp2010/), my colleague [Falk Herwig](http://www.astro.uvic.ca/~fherwig/) and I lay out the case for increased funding of R&D software development by professional research software developers.  We make a couple points which I genuinely believe to be strong:

First, increased benefits. A successful community code can support an enoormous body of research.  By the (admittedly somewhat crude) count we use in this paper, the top six reseach codes in Astronomy accounted for approximately 50% of the computational astronomy publications over the period of study, and the top three - [Cloudy](http://www.nublado.org/), [Gadget](http://www.mpa-garching.mpg.de/galform/gadget/), and [FLASH](http://www.flash.uchicago.edu/site/), which I was part of - accounted for nearly 40%.  That is an enormous about of R&D effort enabled by those projects.

Second, reduced costs. We cite from the growing research software development literature to demonstrate the high (and growing) challenges of engineering these codes in a scientists' spare time, and the high cost of software defects.  By having a small cadre of professional research software development personnel, better quality software can be developed more efficiently.

Finally, a word about the title - this is an analogy due to Falk, and while it's been controversial, I think there's a lot of truth to it.  Astronomy has always relied heavily on, for instance, telescopes - but a telescope is only part of an observational facility.  A big photon-gathering dish is only as useful as the scientific instrument that's placed at its focus to make sense of those photons.  Similarly, a huge computer by itself has no scientific value without software to run on it.  Unless our community invests in computational instruments with the same level of seriousness as observational instruments, our ability to make use of these facilities is going to be needlessly limited.

### Abstract

Modern astronomical research requires increasingly sophisticated computing facilities and software tools. Computational tools have become the fundamental tools to turn observational raw data into scientific insight. Complex multi-physics simulation codes have developed into tools for numerical experiments that provide scientific insight beyond classical theory. Canadian researchers need an environment for developement and maintenance of these critical tools. In particular, the drastically enhanced complexity of deeply heterogeneous hardware architectures poses a real challenge to using present and future HPC facilties.

Without a national program in astrophysical simulation science and astronomy application code developement we are becoming vulnerable with respect to our ability to maximise the scientific return from existing and planned investments into atronomy. In addition, there are significant industrial/commercial HQP needs that simulation and application code program could start to address, if it is properly aligned with academic training opportunities.

We outline the framework and requirements for such a framework for developing Canadian astronomical application and simulation codes — and code builders. In the US decadal plan process, voices are calling for similar emphasis on developing infrastructure and incentives for open community codes (Weiner et al. 2009). We propose funding several small interdisciplinary teams of postdocs, graduate students, and staff, housed in departments at Universities that have or are about to make a commitment in a relevant area (e.g. applied math, computational physics, modeling science). These teams can, while training astronomical and computational HQP, focus on building tools that have been deemed to be high priorities by the astronomical and astrophysical communities in order to make the best scientific use of our new computational faciliites.


```javascript
document.write("JavaScript is a simple language for javatpoint learners");

const map = (arr, callback) => {
  const result = []
  for (let i = 0; i < arr.length; i++) {
    result.push(callback(arr[i], i))
  }
  return result
}
map([1, 2, 3, 4, 5], n => n * 2) // [2, 4, 6, 8, 10]
```