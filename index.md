---
layout: default
---

<div class="page-header">
    <h1>{{ site.title }}</h1>
</div>

<p class="lead">This page gives an overview of the applications and code shared on GitHub by Guildford Borough Council.</p>

Unless otherwise specified all code is written in **C#** for **Microsoft .NET Framework v4.5**.

Some projects have been packaged as [NuGet packages](http://www.nuget.org/) and are available via [this MyGet feed](https://www.myget.org/F/guildford-bc/). Instructions on [how to add a custom package source](http://docs.nuget.org/docs/start-here/managing-nuget-packages-using-the-dialog#Package_Sources) can be found on the Nuget site.

Some of the projects use code that has been written and shared by others. Where this is the case a link to the original source has been included in the code comment.

<div class="row">
  <div class="col-md-3">
    <nav>
      <h3>Contents</h3>
      <h4>Applications</h4>
      <ol class="list-group list-contents list-contents-bottom-divider">
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
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/activedirectory-api">Active Directory API</a> The ASP.NET WebAPI address service</li>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/activedirectory-api-client">Active Directory API Client</a> A wrapper client for the above service</li>
      </ul>
    </article>

    <article id="address">
      <h3>Address</h3>
      <p>This application is a wrapper web service for Aligned Assets SinglePoint product that provides access to the LLPG and OS Addressbase Premium data.</p>
      <h4>Repositories</h4>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address">Address</a> Shared data model for the address API and client <a href="https://www.myget.org/"><img src="https://www.myget.org/BuildSource/Badge/guildford-bc-pre?identifier=ffce863a-4c8e-4fff-981e-e8db6d35abf7" alt="guildford-bc-pre MyGet Build Status" /></a></li>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address-api">Address API</a> The ASP.NET WebAPI address service</li>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address-api-client">Address API Client</a> A wrapper client for the above service <a href="https://www.myget.org/"><img src="https://www.myget.org/BuildSource/Badge/guildford-bc-pre?identifier=32d69c28-af05-4c26-912d-4ef55c176996" alt="guildford-bc-pre MyGet Build Status" /></a></li>
      </ul>
    </article>

    <article id="data-models">
      <h3>Data Models</h3>
      <p>Some standard models for data e.g. a person's name.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/data-models">Data Models</a></li>
      </ul>
    </article>

    <article id="io">
      <h3>IO</h3>
      <p>Method for accessing alternative NTFS data streams and marking files as from the internet (forked from <a href="https://github.com/hubkey/Trinet.Core.IO.Ntfs">Trinet.Core.IO.Ntfs</a>).</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/io">IO</a> <a href="https://www.myget.org/"><img src="https://www.myget.org/BuildSource/Badge/guildford-bc-pre?identifier=0c673302-0d2f-4755-b1e9-0d3a64bd3b17" alt="guildford-bc-pre MyGet Build Status" /></a></li>
      </ul>
    </article>

    <article id="linq">
      <h3>Linq</h3>
      <p>Library of LINQ extension methods.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/linq">Linq</a> <a href="https://www.myget.org/"><img src="https://www.myget.org/BuildSource/Badge/guildford-bc-pre?identifier=45b97ee0-1d3d-4c2d-b4db-17635685f457" alt="guildford-bc-pre MyGet Build Status" /></a></li>
      </ul>
    </article>

    <article id="web-elmah">
      <h3>Web.Elmah</h3>
      <p>Helper methods for adding <a href="https://code.google.com/p/elmah/"><abbr title="Error Logging Modules and Handlers">ELMAH</abbr> error handling</a> to ASP.NET MVC sites, WebAPI services and WCF web services.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/web-elmah">Web.Elmah</a> <a href="https://www.myget.org/"><img src="https://www.myget.org/BuildSource/Badge/guildford-bc-pre?identifier=7dbb7250-a9af-4ca1-9cf5-48be196a0bab" alt="guildford-bc-pre MyGet Build Status" /></a></li>
      </ul>
    </article>

    <article id="web-mvc">
      <h3>Web.Mvc</h3>
      <p>Extensions for ASP.NET MVC projects.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/web-mvc">Web.Mvc</a> <a href="https://www.myget.org/"><img src="https://www.myget.org/BuildSource/Badge/guildford-bc-pre?identifier=d626559b-97b9-4e13-a9db-3fd101caad1a" alt="guildford-bc-pre MyGet Build Status" /></a></li>
      </ul>
    </article>
  </div>
</div>