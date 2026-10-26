<h1 align="center">Casnode (old version)</h1>

<p align="center">
  <a href="https://github.com/casnode/casnode"><img alt="Moved to casnode/casnode" src="https://img.shields.io/badge/moved%20to-casnode%2Fcasnode-0088cc?logo=github"></a>
  <img alt="No longer maintained" src="https://img.shields.io/badge/status-no%20longer%20maintained-lightgrey">
  <a href="https://github.com/casnode/casnode/releases/tag/v1.12.0"><img alt="Last release" src="https://img.shields.io/badge/last%20release-v1.12.0-lightgrey"></a>
</p>

> [!IMPORTANT]
> **This is the old Casnode and it is no longer maintained.** Casnode has been rewritten from scratch as a forum with the
> look and features of Discourse, built with Go and Next.js:
>
> **👉 [github.com/casnode/casnode](https://github.com/casnode/casnode)**
>
> New features, bug fixes and releases (from v2.0.0) happen only there. Please open issues and pull requests in the new
> repository.

## What changed

| | Old Casnode (this repository) | New Casnode |
| --- | --- | --- |
| Look | V2EX-style | Discourse-style: topic lists, timeline, docked composer, user menu |
| Frontend | React single-page app | Next.js, server-rendered pages for search engines |
| Backend | Go + beego | Go + beego, rewritten |
| Database | MySQL | MySQL, PostgreSQL, SQLite or SQL Server |
| Sign-in | Casdoor | Casdoor |
| Versions | up to v1.12.0 | v2.0.0 and later |

The new version uses a different database layout and does not read the tables of the old one, so there is no in-place
upgrade: a site moving to the new Casnode starts with a new forum database. [forum.casbin.com](https://forum.casbin.com)
runs the new version since October 2026.

## Still running the old version?

The code stays here for reference. Its releases, up to
[v1.12.0](https://github.com/casnode/casnode/releases/tag/v1.12.0), remain listed in the new repository, and its
documentation is at
[casnode.org](https://casnode.org). No more fixes will be made, including security fixes, so we recommend moving to the
new Casnode.

## License

[Apache-2.0](LICENSE)
