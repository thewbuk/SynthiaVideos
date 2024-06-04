# Contributing Guidelines

Thank you for your interest in contributing to the Video Database project! We appreciate your efforts to help expand and maintain the database.

## How to Contribute

1. Fork the repository to your own GitHub account.
2. Create a new branch in your forked repository for your changes.
3. Make your changes to the `videos.json` or `channels.json` file, following the specified format.
4. Commit your changes with a descriptive commit message.
5. Push your changes to your forked repository.
6. Open a pull request from your forked repository to the main repository.
7. Provide a clear description of your changes in the pull request.
8. Wait for the project maintainers to review your pull request.
9. Address any feedback or requested changes during the review process.
10. Once your pull request is approved, it will be merged into the main repository.

## Data Format

### Videos

To contribute video data, add your entries to the `videos.json` file in the following format:

```json
{
  "videos": [
    {
      "videoid": "string",
      "channelid": "string",
      "title": "string",
      "description": "string",
      "publishedat": "string"
    }
  ]
}
```
