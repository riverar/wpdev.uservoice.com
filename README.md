# Windows Developer Feedback UserVoice Archive

The Windows Developer Feedback UserVoice forums (wpdev.uservoice.com) will no longer accept submissions after **October 1, 2019**. The forums will go offline **October 28, 2019** and be wiped no later than **November 27, 2019**.

This is a complete archive of the forums, as of **September 28, 2019**.

## Layout

`/forums` contains all four hosted forums:
* `/command-prompt-console-wsl`: Command Prompt / Console / Windows Subsystem for Linux (WSL) (639 items)
* `/microsoft-edge-developer`: Microsoft Edge Developer (1181 items)
* `/universal-windows-platform`: Universal Windows Platform (2649 items)
* `/windows-presentation-foundation`: Windows Presentation Foundation (251 items)

Each forum has two folders within:
* `data`: Contains scraped data in JSON format.
  - Filename format: `[post id].json`
* `screenshots`: 1940px x [1080px minimum] PNG viewport screenshots.
  - Filename format: `[post id].png`

## Annotated JSON Data Example

```jsonc
{
    /* Identifier of post */
    "id": "6509358",

    /* Original link to post */
    "link": "https://wpdev.uservoice.com/forums/266908-command-prompt-console-windows-subsystem-for-l/suggestions/6509358-windows-console-should-support-tabbed-pages",

    /* Post title */
    "title": "Windows Console should support tabbed 'pages'",

    /* Post content (can be blank, contain html) */
    "body": "Great to see some of these improvements, especially the cut/copy/paste keyboard shortcuts. However, I've been seeking for a way for the cmd window to have a tabbed interface for a while. So, for example, I can run a ping/tracert etc. in one tab, a chkdsk in another tab, and something else in a third, without having multiple windows open taking up screen real estate.",

    /* Number of upvotes
       (string is US regional formatted) */
    "votes": "1,660",

    /* Original post author profile link */
    "user": "https://wpdev.uservoice.com/users/57617616-shaun",

    /* Post date/time (yyyy-mm-dd) */
    "datetime": "2014-10-01",

    /* Post comments, 0-[n], in display order */
    "comments": [
        {
            /* Original comment author profile link */
            "user": "https://wpdev.uservoice.com/users/753309160-m-piszczek",

            /* Comment date/time (yyyy-mm-dd) */
            "datetime": "2019-09-27",

            /* Comment content (can be blank, contain html) */
            "body": "The features in Windows Terminal seem very promising but after less than an hour of use it became unresponsive three times (running windows Terminal commands) and crashed twice exiting unexpectedly (connected to a Linux server with ssh). You should emphasize 'now in preview' because this is not at all stable yet."
        }
    ]
}
```