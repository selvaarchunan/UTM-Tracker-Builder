# UTM Tracker Builder

A lightweight web based tool for generating UTM tracking URLs for digital marketing campaigns. Build campaign links for blogs, social media, email newsletters, QR codes and paid advertising.

## Features

- Generate UTM tracking URLs instantly
- Live URL preview as fields change
- Copy generated URLs to the clipboard
- Configure source, medium and campaign parameters
- Add optional campaign content, keywords and campaign IDs
- Preserve existing URL query parameters and fragments
- Responsive interface for desktop and mobile
- Built in explanations of UTM parameters
- Guidance for measuring campaign traffic in Google Analytics 4
- Runs entirely in the browser without sending campaign data to an application server

## Technologies

- HTML5
- CSS3
- JavaScript
- URL and URLSearchParams APIs
- Clipboard API
- Google Analytics 4 campaign tracking concepts

## Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/utm-tracker-builder.git
```

### Open the project

```bash
cd utm-tracker-builder
```

Open `index.html` in your browser, or run a local server:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000`.

## Example Tracking URL

```text
https://example.com/roadshow/calicut?utm_source=from_blog&utm_medium=referral&utm_campaign=expand_north_star_2026&utm_content=calicut
```

### UTM Parameters

| Parameter | Purpose | Example |
|---|---|---|
| `utm_source` | Identifies the traffic source | `from_blog` |
| `utm_medium` | Identifies the marketing channel | `referral` |
| `utm_campaign` | Identifies the campaign | `expand_north_star_2026` |
| `utm_content` | Differentiates links or placements | `calicut` |
| `utm_term` | Identifies a keyword or audience term | `office_keywords` |
| `utm_id` | Optional campaign identifier | `campaign_001` |

## Google Analytics 4

Use tagged campaign links in external marketing channels. In GA4, review Reports → Acquisition → Traffic acquisition to analyse session source, medium and campaign.

UTM parameters identify where traffic comes from. To measure leads or registrations, configure suitable conversion events or key events in GA4.

## Deployment

You can host this static website with GitHub Pages:

1. Upload `index.html` and `README.md` to your repository.
2. Open Settings → Pages.
3. Select the `main` branch and root directory.
4. Save and open the published website URL.

## Privacy

The application generates URLs locally in the browser. It does not send campaign data to an application server. However, the destination website and services used to establish a browser connection may process data according to their own policies.

## Licence

Add an appropriate open source licence if you intend to distribute the project publicly.
