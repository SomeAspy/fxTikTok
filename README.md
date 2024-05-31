# Unchanged version for https://fixtiktok.com

# 📦 fxTikTok

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/okdargy/fxtiktok)

Embed TikTok videos and slideshows on Discord with just `s/i/n`

## Screenshots

<details>
  <summary>Click here to see how fxTikTok looks like</summary>

| <img src="https://raw.githubusercontent.com/okdargy/fxTikTok/master/.github/readme/compare.png" alt="Video Preview" width="90%" height="90%"/> |
| :--------------------------------------------------------------------------------------------------------------------------------------------: |
|                                           Comparing `tiktok.com` vs. `tnktok.com` embeds on Discord                                            |

| <img src="https://raw.githubusercontent.com/okdargy/fxTikTok/master/.github/readme/slideshow.png" alt="Slideshow Preview" /> |
| :--------------------------------------------------------------------------------------------------------------------------: |
|                                                       Slideshow embeds                                                       |

| <img src="https://raw.githubusercontent.com/okdargy/fxTikTok/master/.github/readme/live.png" alt="Live Preview" /> |
| :----------------------------------------------------------------------------------------------------------------: |
|                                                 Live video embeds                                                  |

| <img src="https://raw.githubusercontent.com/okdargy/fxTikTok/master/.github/readme/direct.png" alt="Direct Preview" /> |
| :--------------------------------------------------------------------------------------------------------------------: |
|                                               Direct image/video support                                               |

</details>

## Usage

Using fxTikTok is easy on Discord. Fix ugly and unresponsive embeds by sending your TikTok link and then typing `s/i/n`

### How does this work?

When you send `s/i/n` in Discord, it modifies your most recent message using the [sed](https://www.gnu.org/software/sed/manual/sed.html) format. Specifically, it replaces the first occurrence of the second parameter (`i`) in the message with the third parameter (`n`).

|     Before     |     After      |
| :------------: | :------------: |
| t**i**ktok.com | t**n**ktok.com |

### Using Direct Embeds

Don't want all that statistic clutter on your embed and only want the video or image? Simply change your URL to `d.tnktok.com`

|         Before         |        After         |
| :--------------------: | :------------------: |
| **www**.t**i**ktok.com | **d**.t**n**ktok.com |

> Alternatively, you can also set `isDirect` to true thru the URL query by adding `?isDirect=true` at the end of your URL

### Why use tnktok.com?

We check all the boxes for being one of the best TikTok embedding services with many features that others don't have. Here's a table comparing our service, tnktok.com, with the other TikTok embedding services as well as TikTok's default embeds.

|                                        | [tnktok.com](https://www.tnktok.com) | Default TikTok | [tiktxk.com](https://tiktxk.com) | [vxtiktok.com](https://vxtiktok.com) | [tfxktok.com](https://tfxktok.com) |
| -------------------------------------- | ------------------------------------ | -------------- | -------------------------------- | ------------------------------------ | ---------------------------------- |
| Embed playable videos                  | ☑️                                   | ❌             | ❔                               | ☑️                                   | ☑️                                 |
| Embed multi-image slideshows           | ☑️                                   | ❌             | ❔                               | ❌                                   | ☑️                                 |
| Embed lives                            | ☑️                                   | ➖             | ❌                               | ❌                                   | ☑️                                 |
| Open source                            | ☑️                                   | ❌             | ☑️                               | ☑️                                   | ❌                                 |
| Supports direct embeds                 | ☑️                                   | ❌             | ❌                               | ❌                                   | ❌                                 |
| Shows like, shares, comments           | ☑️                                   | ➖             | ➖                               | ☑️                                   | ☑️                                 |
| Removes tracking for redirects         | ☑️                                   | ❌             | ☑️                               | ☑️                                   | ☑️                                 |
| Support for multi-continent short URLs | ☑️                                   | ☑️             | ☑️                               | ☑️                                   | ❌                                 |
| Support for h265/high quality          | ☑️                                   | ❌             | ❔                               | ❌                                   | ❌                                 |
| Last commit                            | [![][tnk]][tnkc]                     | N/A            | [![][txk]][txkc]                 | [![][vxt]][vxtc]                     | N/A                                |

[tnk]: https://img.shields.io/github/last-commit/okdargy/fxTikTok?label
[tnkc]: https://github.com/okdargy/fxTikTok/commits
[txk]: https://img.shields.io/github/last-commit/Britmoji/tiktxk?label
[txkc]: https://github.com/Britmoji/tiktxk/commits
[vxt]: https://img.shields.io/github/last-commit/dylanpdx/vxtiktok?label
[vxtc]: https://github.com/dylanpdx/vxtiktok/commits
