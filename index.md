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
      <h4>Frontend</h4>
      <ol class="list-group list-contents list-contents-bottom-divider">
          <li class="list-group-item"><a href="#front-assets">Front assets</a></li>
          <li class="list-group-item"><a href="#front-template">Front template</a></li>
      </ol>
      <h4>Libraries</h4>
      <ol class="list-unstyled list-contents list-contents-bottom-divider">
          <li class="list-group-item"><a href="#data-models">Data Models</a></li>
          <li class="list-group-item"><a href="#io">IO</a></li>
          <li class="list-group-item"><a href="#linq">Linq</a></li>
          <li class="list-group-item"><a href="#web-mvc">Web MVC</a></li>
          <li class="list-group-item"><a href="#web-mvc-html">Web MVC HTML</a></li>
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
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/activedirectory-api-client">Active Directory API Client</a> A wrapper client for the above service <a href="https://ci.appveyor.com/project/guildford-bc/activedirectory-api-client" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/hd7rsgur4gafi326" title="Build status"></a></li>
      </ul>
    </article>

    <article id="address">
      <h3>Address</h3>
      <p>This application is a wrapper web service for Aligned Assets SinglePoint product that provides access to the LLPG and OS Addressbase Premium data.</p>
      <h4>Repositories</h4>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address">Address</a> Shared data model for the address API and client <a href="https://ci.appveyor.com/project/guildford-bc/address" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/n62vnfad3xkq6xd8" title="Build status"></a></li>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address-api">Address API</a> The ASP.NET WebAPI address service</li>
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/address-api-client">Address API Client</a> A wrapper client for the above service  <a href="https://ci.appveyor.com/project/guildford-bc/address-api-client" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/4j6tmavwdo5v25gm" title="Build status"></a></li>
      </ul>
    </article>

    <article id="data-models">
      <h3>Data models</h3>
      <p>Some standard models for data e.g. a person's name.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/data-models">Data Models</a></li>
      </ul>
    </article>

    <article id="front-assets">
      <h3>Front assets</h3>
      <p>Static files/resources for GUILDFORD.GOV.UK front ends. <a href="/front-assets/">More information</a>.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/front-assets">Front assets</a> <a href="https://ci.appveyor.com/project/guildford-bc/front-assets" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/s05gh926b1jes13i?svg=true" title="Build status"></a></li>
      </ul>
    </article>

    <article id="front-template">
      <h3>Front template</h3>
      <p>.NET Razor template for MVC web applications. <a href="/front-template/">More information</a>.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/front-template">Front template</a> <a href="https://ci.appveyor.com/project/guildford-bc/front-template" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/553b9tak9hevbckv?svg=true" title="Build status"></a></li>
      </ul>
    </article>

    <article id="io">
      <h3>IO</h3>
      <p>Method for accessing alternative NTFS data streams and marking files as from the internet (forked from <a href="https://github.com/hubkey/Trinet.Core.IO.Ntfs">Trinet.Core.IO.Ntfs</a>).</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/io">IO</a></li>
      </ul>
    </article>

    <article id="linq">
      <h3>Linq</h3>
      <p>Library of LINQ extension methods.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/linq">Linq</a> <a href="https://ci.appveyor.com/project/guildford-bc/linq" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/c0fr2iegvtf2v54x?svg=true" title="Build status"></a></li>
      </ul>
    </article>

    <article id="web-mvc">
      <h3>Web.Mvc</h3>
      <p>Extensions for ASP.NET MVC projects.</p>
      <ul class="list-unstyled list-contents list-contents-top-divider">
        <li class="list-group-item"><a href="https://github.com/GuildfordBC/web-mvc">Web.Mvc</a> <a href="https://ci.appveyor.com/project/guildford-bc/web-mvc" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/f574t0v0lhwm9rwn?svg=true" title="Build status"></a></li>
      </ul>
    </article>
    
    <article id="web-mvc-html">
        <h3>Web.Mvc.Html</h3>
        <p>HTML extensions for MVC</p>
        <ul class="list-unstyled list-contents list-contents-top-divider">
            <li class="list-group-item"><a href="https://github.com/GuildfordBC/web-mvc-html">Web.Mvc.Html</a> <a href="https://ci.appveyor.com/project/guildford-bc/web-mvc-html" class="pull-right"><img src="https://ci.appveyor.com/api/projects/status/auf7q6qy2jl7jii0?svg=true" title="Build status"></a></li>
        </ul>
    </article>
    
  </div>
</div>
