## Hi there 👋

🙋‍ This is blazingfasthttp.com, a personal software packaging project for high-performance HTTP server software for Enterprise Linux distributions. Currently, I'm targeting only nginx/openresty third-party modules but may evolve later to Varnish and other related stuffs.

So :
- I provide binary-compatible modules packages with official repository (nginx.org and openresty.org) binaries
- Current target distribution are CentOS and AlmaLinux (CloudLinux and other RHEL based distro should be compatible too). Old EOL distribution is not supported.
- RPM are hosted on a public repository accessible for free

## Why blazingfasthttp.com?
Because I didn't found any **free** nginx repository providing modules I want. I decided to make it. As simple as it.

## Current available packages
### OpenResty
These modules are intendeed to be binary compatible with OpenResty official binaries provided in their repository.
- Repository URL: https://packagecloud.io/manoaratefy/openresty-extras
- Available package:
  - [openresty-module-brotli](https://github.com/blazingfasthttp/openresty-module-brotli): refers to [ngx_brotli](https://github.com/google/ngx_brotli)
### Nginx
Work in progress.

## Support
This is a *personal side-project*  where I don't really put time to work on, and I consider I'm not enough experienced about repository maintaining. If you are looking for more professional way to get these Nginx/Openresty packages, I'll suggest you to go with paid repository like GetPageSpeed who know what they do.

As this is a simple side-project and I have full-time job besides, I'm do my best for maintaining but don't expect to have a 24/7 support. So, don't expect that I release new versions in few hours after a new release is made by a module or by Nginx/OpenResty. 😛

## Contribution guidelines
I never maintained open-source project previously. Be kind, don't hesitate to make *useful* remarks in issues reporting. PR and suggestions is highly appreciated.
