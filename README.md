# myaur

自用修改版PKGBUILD。AUR里的PKGBUILD确实好用，但是默认build的东西包括了我不需要的组件，因为是个性化需求，所以不方便放到AUR上。另一些则是简单的洁癖，根据最新Guideline修改了语法。

1. sing-box-git，直接编译sing-box的最新版，但是不包括任何额外组件。原因：utls导致很多问题，包括用chrome访问部署了cloudflare DDoS防护的网站会导致无限循环“我是真人”验证、App Store无法访问等。

# 参考标准

1. [AUR submission guidelines](https://wiki.archlinux.org/title/AUR_submission_guidelines)
1. [Arch package guidelines](https://wiki.archlinux.org/title/Arch_package_guidelines)
1. [VCS package guidelines](https://wiki.archlinux.org/title/VCS_package_guidelines)