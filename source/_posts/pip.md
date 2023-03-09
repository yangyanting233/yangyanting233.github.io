---
title: pip
---
<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Install package from github](#install-package-from-github)

<!-- /code_chunk_output -->

## Install package from github

Ref: [VCS Support](https://pip.pypa.io/en/stable/topics/vcs-support/)

```bash
pip install git+https://gitprovider.com/user/project.git@{version}
```

Or if your repository is private:

```bash
pip install git+ssh://git@gitprovider.com/user/project.git@{version}
```
