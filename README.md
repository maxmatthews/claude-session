# claude-session

A one-page redirect so Claude desktop session links can be clicked from GitHub. GitHub strips `claude://` hrefs from Markdown.

`https://maxmatthews.github.io/claude-session/#<sessionId>` opens `claude://claude.ai/epitaxy/<sessionId>`.

The page contains no session content. Sessions stay on the machine that ran them, and the link only opens in that person's Claude app. The page only forwards to `claude://claude.ai/epitaxy/` followed by an ID matching `[A-Za-z0-9_-]{1,128}`. It refuses anything else.
