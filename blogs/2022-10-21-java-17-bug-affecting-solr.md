---
title: "Java 17 bug affecting Solr"
url: "/java-17-bug-affecting-solr.html"
date: "2022-10-21"
author: "Solr Developers"
feed_url: "https://solr.apache.org/feeds/solr/news.atom.xml"
---
Several users running Solr in production on OpenJDK 17 have experienced JVM crashes due to a known bug in the JDK. Read more about the bug in SOLR-16463 . Known mitigations are to either downgrade to JDK 11 or to start Solr with a Java startup flag that avoids the failure …
