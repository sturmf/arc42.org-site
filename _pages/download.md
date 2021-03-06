---
title: "Download arc42"
layout: splash
permalink: /download
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/splash/unsplash-download-pedro-lastra.jpg
  caption: "Photo credit: [**Pedro Lastra**](https://unsplash.com/photos/5g8dJvtYRYA/)"
excerpt: "Version 7.0 - the most practical and effective arc42 ever."

intro:
  - excerpt: "Version 7.0, released January 20th 2017."


---

{% include feature_row id="intro" type="center" %}

{% include toc %}

On this page you find all available arc42 template downloads,
various formats for various tools.

{% assign PREFIX = "https://github.com/arc42/arc42-template/raw/master/dist/arc42-template-" %}

## File-based formats

{% assign formats = "docx|asciidoc|markdown|latex|html|textile" | split: "|"  %}  
{% assign types = "plain|withhelp" | split: "|"  %}  

| Format | Language | Plain | With Help |
|--------|----------|-------|-----------|
{% for format in formats %}| {{ format }} | EN | {% for type in types %} [.zip]({{PREFIX}}EN-{{type}}-{{format}}.zip) |{% endfor %}
|  | DE | {% for type in types %} [.zip]({{PREFIX}}DE-{{type}}-{{format}}.zip) |{% endfor %}
{% endfor %}

## Confluence format
Confluence versions are generated _with help_ and come in
two flavors:

* flat: all sections on a single page
* structured: one Confluence page per arc42-section


| Language | flat | structured |
|----------|------|------------|
| DE | [.zip]({{PREFIX}}DE-withhelp-confluenceFlat.zip) | [.zip]({{PREFIX}}DE-withhelp-confluenceStructured.zip) |
| EN | [.zip]({{PREFIX}}EN-withhelp-confluenceFlat.zip) | [.zip]({{PREFIX}}EN-withhelp-confluenceStructured.zip) |

These versions are generated for the latest version of confluence
(we test with our own [cloud-hosted confluence](https://arc42-template.atlassian.net/)
  provided by Atlassian.)

**Notes for Confluence users**

* If you consider to use confluence, the [asciidoc2confluence](https://github.com/rdmueller/asciidoc2confluence) script might be helpful.

* There is also a [confluence plugin available from the atlassian market place](https://marketplace.atlassian.com/plugins/com.networkedassets.plugins.space-blueprint/server/overview).

## Legacy Version (arc42 v6) for Confluence  

If you still use confluence version 4 or 5, these legacy downloads might help you
(currently from Dropbox - we're moving this to the Github repo any day now)

| Confluence version | Language  | With Help |
|--------|-----------|-----------|
|5.x | EN |  [.zip](https://www.dropbox.com/s/yvlkkozpt36rovr/templateEN-V6-confluence-53.xml.zip?dl=0)|
|>4.3 | EN | [.zip](https://www.dropbox.com/s/9ss7s1h24ikyx5d/templateEN-V6-confluence-43.xml.zip?dl=0)|
|5.x | DE | [.zip](https://www.dropbox.com/s/phz6fgdas2p320a/templateDE-V6-confluence-53.xml.zip?dl=0)|
|>4.3 | DE | [.zip](https://www.dropbox.com/s/x7n456bw8i8dl97/templateDE-V6-confluence-43.xml.zip?dl=0) |

These legacy versions have been provided (thanx!) by arc42 users - and can
not be supported by us (as we don't have access to these legacy Confluence versions).
{: .small}


## Enterprise Architect&copy; format
Enterprise Architect;copy; is a commercial UML modeling tool by
SparxSystems.

The Enterprise-Architect version of arc42 contains the plain
arc42 structure without help text.

&lt; to be done >

## Formats for other modeling tools
We currently don't support additional modeling tools - but would love to...
In case you use arc42 with such a tool, please think about contributing :-)

Please [contact us!](/contact)
