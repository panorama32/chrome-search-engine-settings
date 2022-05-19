# chrome-search-engine-settings

僕のChromeの検索エンジン設定。

`chrome://settings/searchEngines`を開いて「サイト内検索」から追加をする。

# Google

Google検索を英語でする。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| Google EN | en | {google:baseURL}search?q=%s&gl=us&hl=en |

`gl`: 国を指定する。指定することでその国から検索した結果が得られる。

`hl`: ページを表示する言語。

# GitHub

GitHubでリポジトリを検索。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| GitHub | github | https://github.com/search?q=%s |

# GitHub Your Repository

GitHubで自分のリポジトリを検索。

$YOUR_GITHUB_USERNAMEには自分のユーザーネームを入れる。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| GitHub Repos | github-my-repos | https://github.com/$YOUR_GITHUB_USERNAME?tab=repositories&q=%s |

# Pocket

Pocketのタグで検索。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| Pocket | pocket | https://getpocket.com/ja/my-list/tags/%s |

# Twitter

IDからのツイートで検索。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| Twitter | twitter | https://twitter.com/search?q=from%3A%s |

# YouTube

YouTube動画の検索。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| YouTube | youtube | https://www.youtube.com/results?search_query=%s |

# Qiita

Qiita記事の検索。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| Qiita | qiita | https://qiita.com/search?q=%s |

# pkg.go.dev

GolangのPackageを検索。

| 検索エンジン | ショートカット | URL (%s=検索語句) |
| -- | -- | -- |
| pkg.go.dev | go | https://pkg.go.dev/search?q=%s |
