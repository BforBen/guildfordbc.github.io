---
layout: default
---

<div class="page-header">
    <h1>{{ site.title }}</h1>
</div>

## Applications

<div class="row">
  <div class="col-md-3">
    <nav>
      <h3>Contents</h3>
      <ol class="list-group list-contents">
          <li class="list-group-item"><a href="#active-directory">Active Directory</a></li>
          <li class="list-group-item"><a href="#address">Address</a></li>
      </ol>
      <h4>Libraries</h4>
      <ol class="list-unstyled list-contents list-contents-bottom-divider">
          <li class="list-group-item"><a href="#data-models">Data Models</a></li>
          <li class="list-group-item"><a href="#io">IO</a></li>
          <li class="list-group-item"><a href="#linq">Linq</a></li>
          <li class="list-group-item"><a href="#web-elmah">Web Elmah</a></li>
          <li class="list-group-item"><a href="#web-mvc">Web MVC</a></li>
      </ol>
    </nav>
  </div>

  <div class="col-md-8 col-md-offset-1">
    <article id="active-directory">
      <h3>Active Directory</h3>
      <p>This application is a web service for accessing Active Directory user and group information.</p>
      <h4>Repositories</h4>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/activedirectory-api">Active Directory API</a> The ASP.NET MVC WebAPI address service</dd>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/activedirectory-api-client">Active Directory API Client</a> A wrapper client for the above service</li>
      </ul>
    </article>

    <article id="address">
      <h3>Address</h3>
      <p>This application is a wrapper web service for Aligned Assets SinglePoint product that provides access to the LLPG and OS Addressbase Premium data.</p>
      <h4>Repositories</h4>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address">Address</a> Shared data model for the address API and client</li>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address-api">Address API</a> The ASP.NET MVC WebAPI address service</li>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address-api-client">Address API Client</a> A wrapper client for the above service</li>
      </dl>
    </article>
  </div>
</div>