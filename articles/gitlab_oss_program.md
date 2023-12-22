---
title: "GitLab for Open Source Programに登録しようぜ"
emoji: "🧑‍💻"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["GitLab", "OSS", "CICD"]
published: true
---

:::message

この記事は、[GitLab Advent Calendar 2023](https://qiita.com/advent-calendar/2023/gitlab)の20日目の記事になります。

:::

https://qiita.com/advent-calendar/2023/gitlab

# TL;DR

- [GitLab.com](https://gitlab.com/)のFreeアカウントで使える[GitLab CI](https://docs.gitlab.com/ee/ci/)の時間は400分。
- [GitLab for Open Source](https://about.gitlab.com/solutions/open-source/)に登録すると[GitLab Ultimate](https://about.gitlab.com/solutions/open-source/#:~:text=potential.%20Features%20of-,GitLab%20Ultimate,-%E2%80%94including%2050%2C000%20compute)の機能が開放されるので[GitLab CI](https://docs.gitlab.com/ee/ci/)の時間は50,000分になる。
- [GitLab for Open Source](https://about.gitlab.com/solutions/open-source/)は、OSSライセンス設定しているPublicリポジトリなら登録できる。

# [GitLab CI](https://docs.gitlab.com/ee/ci/)のCompute quota

GitLab v16.1までは、`CI/CD minutes`と呼ばれていました。  
要するに[GitLab CI](https://docs.gitlab.com/ee/ci/)の共用Runnerを動かせる時間です。  
[アカウント種別](https://about.gitlab.com/pricing/)によって時間は異なるが、Freeアカウントであれば400分使用できる。

![](https://storage.googleapis.com/zenn-user-upload/9320e26d09d6-20231223.png)

> 昔はPublicなOSSリポジトリは、`CI/CD minutes`にかなり長めの時間が設定されていたが、マイニング対策か[制限時間が設定された](https://about.gitlab.com/blog/2020/09/01/ci-minutes-update-free-users/)。

# [GitLab for Open Source Program](https://about.gitlab.com/solutions/open-source/)

[GitLab for Open Source Program](https://about.gitlab.com/solutions/open-source/)に参加できれば、self-managedまたはSaaS版のGitLabで[GitLab Ultimate](https://about.gitlab.com/solutions/open-source/#:~:text=potential.%20Features%20of-,GitLab%20Ultimate,-%E2%80%94including%2050%2C000%20compute)の機能が開放されます。

:::message

self-managed版GitLabは、Runnerも自前用意なのでCompute quotaに関する恩恵はなし。

:::

## 参加条件

GitLab for Open Source Programへの参加条件は3つ[^1]です。

1. MITライセンスなどの **[OSI Approved Licenses](https://opensource.org/licenses/)を設定していること**
2. **非営利であること**
3. **Publicリポジトリであること**

一般的なOSSリポジトリであれば、上記条件は自然と満たしています。
