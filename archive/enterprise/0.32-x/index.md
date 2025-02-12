---
title: Documentation for Kong Gateway (Enterprise)
subtitle: Formerly known as Kong Enterprise, now part of Kong Konnect
is_homepage: true
---
# Welcome to Kong Enterprise Edition

{% if page.edition == 'enterprise' %}
<div class="alert alert-ee">
  <div class="alert-body">
    <div class="left">
      <img src="/assets/images/icons/icn-buildings.svg" />
    </div>
    <p>Kong Enterprise Edition (EE) adds features, functionality, and performance to Kong Community Edition (CE). This documentation doesn’t cover the general practices of using Kong that are common to both Kong CE and EE - learn the <a href="">basics in Kong CE documentation</a>.</p>
  </div>
</div>
{% endif %}

<div class="docs-grid">
  <div class="docs-grid-block">
    <h3><img src="/assets/images/icons/documentation/icn-window.svg" /><a href="/enterprise/{{page.kong_version}}/kong-implementation-checklist">Implementation Checklist</a></h3>
    <p>Advice for planning your Kong Enterprise Edition deployment.</p>
    <a href="/enterprise/{{page.kong_version}}/kong-implementation-checklist">Go to Checklist &rarr;</a>
  </div>

  <div class="docs-grid-block">
    <h3><img src="/assets/images/icons/documentation/icn-window.svg" /><a href="/gateway/changelog">Changelog</a></h3>
    <p>Details of the changes to each version of Kong Enterprise Edition.</p>
    <a href="/gateway/changelog/">See changelog &rarr;</a>
  </div>

  <div class="docs-grid-block">
    <h3><img src="/assets/images/icons/documentation/icn-window.svg" /><a href="/enterprise/{{page.kong_version}}/kong-architecture-overview/">Architecture Overview</a></h3>
    <p>Learn about the architecture of Kong, its dependencies, and related systems.</p>
    <a href="/enterprise/{{page.kong_version}}/kong-architecture-overview/">Learn more &rarr;</a>
  </div>

  <div class="docs-grid-block">
    <h3><img src="/assets/images/icons/documentation/icn-window.svg" /><a href="/enterprise/{{page.kong_version}}/installation/docker/">Docker</a></h3>
    <p>Kong Enterprise Edition is quick and easy to run via Docker.</p>
    <a href="/enterprise/{{page.kong_version}}/installation/docker">Run Kong via Docker &rarr;</a>
  </div>

  <div class="docs-grid-block">
    <h3><img src="/assets/images/icons/documentation/icn-window.svg" /><a href="/enterprise/{{page.kong_version}}/installation/amazon-linux">Amazon Linux</a></h3>
    <p>Run Kong Enterprise Edition on AWS.</p>
    <a href="/enterprise/{{page.kong_version}}/installation/amazon-linux/">Run Kong via Amazon Linux &rarr;</a>
  </div>

  <div class="docs-grid-block">
    <h3><img src="/assets/images/icons/documentation/icn-window.svg" /><a href="/enterprise/{{page.kong_version}}/admin-gui/">Accessing Admin GUI</a></h3>
    <p>Kong’s Admin GUI makes it quick and easy to configure and understand Kong Enterprise Edition.</p>
    <a href="/enterprise/{{page.kong_version}}/admin-gui/">Learn more &rarr;</a>
  </div>

  <div class="docs-grid-block">
    <h3><img src="/assets/images/icons/documentation/icn-window.svg" /><a href="/enterprise/{{page.kong_version}}/setting-up-admin-api-rbac/">Setting Up Admin API RBAC</a></h3>
    <p>Advice for planning your Kong Enterprise Edition deployment.</p>
    <a href="/enterprise/{{page.kong_version}}/setting-up-admin-api-rbac/">Setup RBAC &rarr;</a>
  </div>
</div>
