# 02 – Make.com Facebook Automation

## Overview

An automated Facebook publishing workflow built with Make.com.

## Features

- **Automated publishing** – publishes posts with images and captions.
- **Google Drive integration** – retrieves images and post descriptions.
- **Duplicate prevention** – tracks published posts in `POSTED.json`.
- **Discord notifications** – alerts when fewer than 10 unpublished posts remain.
- **Scheduled execution** – runs daily at 12:30 and 21:30 (Europe/Warsaw).

## Workflow

1. Download and parse `POSTED.json`.
2. Search for unpublished posts in Google Drive.
3. Retrieve the selected post's image and description.
4. Publish the post to Facebook.
5. Update `POSTED.json` with the published post.
6. Send a Discord notification when the remaining content falls below the configured threshold.

## Technologies

- Make.com
- Google Drive
- Facebook Pages
- Discord
- JSON
- JavaScript
