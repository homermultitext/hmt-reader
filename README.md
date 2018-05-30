# HMT Text Reader

This directory includes compiled, optimized versions of the CITEApp, including all necessary CSS and  javascript in a single `.html` file.

It is pre-configured to load a digital library containing a sub-set of the **Homer Multitext 2018 D** data release. That library is also included in this directory, `hmt-2018d-texts.cex`.

An [overview of the Homer Multitext data is online](https://github.com/homermultitext/hmt-archive). The subset of that data available through this application consists of the currently published texts of the *Iliad* and scholia from the Venetus A manuscript, and indexing information associating commentary texts with passages of the poem.

[An online interface to the complete HMT 2018d data](http://www.homermultitext.org/cite-app/), including manuscript images and other indexed data is available for online viewing. All Homer Multitext data is available for download from [the archive]((https://github.com/homermultitext/hmt-archive), and all images published by the HMT is available from our [server at the University of Houston](http://amphoreus.hpcc.uh.edu).

## Running

- Double-click on `hmt-reader.html` to open it in a browser.
- If there is an active internet connection, the app will automatically fetch and load the HMT library in `.cex` form [from the online archive](https://github.com/homermultitext/hmt-archive/tree/master/releases-cex).

## Running (Offline)

- Double-click on `hmt-reader.html` to open it in a browser.
- Use the `Choose File` button at the to select and open a `hmt-2018d-texts.cex` file.

## Versions

- HMT 2018d
- CiteApp 1.10.0

## Reference

This app is based on the [CITE Architecture](http://cite-architecture.github.io), a protocol for identification and retrieval of data via machine-actional canonical citations in URN format.

CITE/CTS is ©2002–2017 Neel Smith and Christopher Blackwell. This implementation of the CITE data models was written by Neel Smith and Christopher Blackwell using <a href="https://www.scala-lang.org">Scala</a>, <a href="http://www.scala-js.org">Scala-JS</a>, and <a href="https://github.com/ThoughtWorksInc/Binding.scala">Binding.scala</a>. Licensed under the <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GPL 3.0</a>. Sourcecode on <a href="https://github.com/cite-architecture/ScalaJS-CITE-Environment">GitHub</a>.
