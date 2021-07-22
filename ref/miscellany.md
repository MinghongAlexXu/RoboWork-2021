[scp or sftp copy multiple files with single command](https://stackoverflow.com/questions/16886179/scp-or-sftp-copy-multiple-files-with-single-command)

[How to run a Linux Program on Startup](https://timleland.com/how-to-run-a-linux-program-on-startup/)

[How To Use Systemctl to Manage Systemd Services and Units](https://www.digitalocean.com/community/tutorials/how-to-use-systemctl-to-manage-systemd-services-and-units)

[How to execute a program or call a system command from within a Python script?](https://stackoverflow.com/questions/89228/how-to-execute-a-program-or-call-a-system-command)

[import 问题浅谈](https://zhuanlan.zhihu.com/p/69099185)

[史上最详细的包和模块import讲解篇](https://jishuin.proginn.com/p/763bfbd22f68)

[ModuleNotFoundError: No module named](https://www.cnblogs.com/yifanrensheng/p/13979064.html)

> [What's wrong with relative imports in Python?](https://softwareengineering.stackexchange.com/questions/159503/whats-wrong-with-relative-imports-in-python)
>
> Note you can also do import .icing instead of from . import icing
>
> I don't think you can. From this part of PEP328:
> Relative imports must always use from <> import ; import <> is always absolute.
> Of course, absolute imports can use from <> import by omitting the leading dots.
> The reason import .foo is prohibited is because after import XXX.YYY.ZZZ then XXX.YYY.ZZZ is usable in an expression,
> but .moduleY is not usable in an expression.


> It’s important to keep in mind that all packages are modules, but not all modules are packages. 
> Or put another way, packages are just a special kind of module. 
> Specifically, any module that contains a \_\_path__ attribute is considered a package.

[Github Desktop no longer support "Git Shell"](https://stackoverflow.com/questions/34565238/where-does-github-desktop-install-command-line-version-of-git/54679083#54679083)

[What are we gonna do about Git Shell on Windows](https://github.com/desktop/desktop/issues/340)

[]()