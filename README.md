# Baguio Dash: Fun Run Survey

A responsive, browser-based survey for collecting participant feedback about the Baguio Dash fun run. The form gathers attendee details, event ratings, highlights, likelihood to return, and optional comments.

## Features

- Responsive layout for desktop and mobile screens
- Participant information fields with built-in HTML validation
- Radio-button ratings, multi-select checkboxes, a return-likelihood dropdown, and an optional comments field
- Submission and error-status messages
- Google Apps Script form submission endpoint
- Built with plain HTML and CSS, with lightweight JavaScript for form behavior

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Apps Script endpoint for form submissions

## Live demo

Try the survey: [Baguio Dash: Fun Run Survey](https://rullan-harvey-laurence.github.io/Fun-Run-Survey/)

## Form submissions

The form sends a `POST` request to the Google Apps Script URL configured in the `action` attribute of the form in `index.html`. Before using the project for a live event, verify that the endpoint is your intended deployment and that it is configured to receive submissions.

The form collects personal information, including a participant's name, age, and email address. Configure the receiving service and access to submitted data appropriately, and provide participants with relevant privacy information.

## Deployment

This is a static site and can be hosted on GitHub Pages or another static web host. On GitHub, open the repository's **Settings → Pages**, select the branch and folder containing `index.html` (typically the root folder), and save.

## Project structure

```text
.
├── index.html   # Survey markup and form-submission behavior
├── style.css    # Layout, responsive styling, and visual design
└── README.md    # Project documentation
```

## Contributing

Suggestions and improvements are welcome. Open an issue to discuss a change, or submit a pull request with a clear description of what it improves.

## License

No license file is currently included. Unless a license is added, standard copyright applies and reuse, distribution, or modification is not granted by default. Add a `LICENSE` file if you want to specify terms for reuse.
