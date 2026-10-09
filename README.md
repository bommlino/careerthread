# CareerThread

Proposed personal, non-commercial, read-only Reddit application
for finding employer and salary discussions during my own job search.

## Status
Planning stage. Reddit Data API access approval requested.
No Reddit API access or data collection has been implemented.

## Planned workflow
- Local Python application.
- User-initiated keyword searches across a small subreddit allowlist.
- Retrieval of selected public threads and limited comments.
- Private local CSV or Markdown exports.
- No posting, messaging, voting, or moderation actions.

## Proposed limits
- Maximum 100 API requests per day.
- Maximum 5 API requests per minute.
- Maximum 20 selected threads per day.
- No bulk collection or historical backfill.

## Data handling
- No public dataset or redistribution.
- No user profiling.
- Cached post/comment text retained for at most 30 days.
- Deleted or removed cached content will be removed.
- No external AI processing or model training in the initial version.
