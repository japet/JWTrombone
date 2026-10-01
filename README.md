# JW's Trombone Equipment

A historical static equipment page. `index.html` is the entire site; it embeds
an Amazon affiliate product iframe and explains the affiliate relationship.
There is no package manager, build step or automated test suite.

## Preview and review

Run `python3 -m http.server 8000 --bind 127.0.0.1` in this checkout, then open
<http://127.0.0.1:8000/>. Stop with Ctrl-C. Do not serve a parent directory or add
private files. Loading the page can contact Amazon through the embedded iframe;
block external requests when inspecting only the local markup.

Check the heading, disclosure, product frame and small-screen layout. A missing
iframe is not proof the local server failed: the external legacy widget may be
unavailable or blocked. Outbound product availability and affiliate behavior
have not been verified. Do not make purchases as a test.

## Next work requires an owner decision

Confirm whether the page is still intended for use, who owns its hosting, and
whether the equipment and affiliate links are current. No hosting configuration
or deployment procedure is present in this repository, so do not infer a live
site or publish changes from this preview recipe. If continuing, replace or
validate the legacy widget and record the approved hosting/update procedure.
