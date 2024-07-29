# Building a Secure and Productive TRE: How I Learned to Stop Worrying and Proxy PyPI

A talk presented at RSECon24.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Abstract

How can we achieve the right balance between security and productivity in research with sensitive data?

The world is awash with data that can be used to provide insights that benefit society.
However, much of this data is effectively unavailable for use by researchers due to privacy concerns.

Unlocking access to this data requires building trust with the custodians who safeguard the data and with society as a whole.
Traditionally, this trust has been secured by a "security maximalist" approach, either by design, or through excessive caution.

Here, we share the lessons of 6 years of working with over 50 data providers to support access to sensitive data for research under a flexible framework of information governance and technical controls.

We've built an open source information governance framework and reproducibly-deployable, cloud-based Trusted Research Environment (TRE).

In this talk we discuss:

- Making governance and security controls explainable to data risk holders
- Using a tiered risk model to help achieve shared consensus
- Supporting researcher effectiveness
- Where security and usability _don't_ end up being a trade-off
- The things you *don't* need in a locked-down environment
- The value of sharing governance models and TRE design choices openly
- The power of collaborating as a community to address shared challenges

Drawing on our experience, we will set out what a good balance between competing concerns looks like, what we do differently to other TREs, and how you can get involved with both our work and the wider TRE community.
