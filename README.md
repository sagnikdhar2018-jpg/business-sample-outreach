# Business Sample Outreach

A Codex skill for turning one business or a lead spreadsheet into AI-generated product samples and personalized outreach. Each business gets its own creative direction, labeled images, and a pitch for a short promotional video.

## Install

1. [Download the skill ZIP](https://github.com/sagnikdhar2018-jpg/business-sample-outreach/releases/latest/download/business-sample-outreach.zip) and extract it.
2. Copy the extracted business-sample-outreach folder into your Codex skills directory. Use $CODEX_HOME/skills if configured, or ~/.codex/skills by default.
3. Invoke **$business-sample-outreach** in Codex and provide a business name, website, or lead spreadsheet.

## Example

> Use $business-sample-outreach with my lead spreadsheet. Sign the pitches as Alex, create seven labeled samples per business, and prepare Gmail drafts for review.

The workflow uses image generation for samples and connected Gmail for drafts and sending. You can set the sender name, number of images, and payment offer. Sending requires explicit authorization for the recipients covered by the request.

## License

[MIT](LICENSE) covers this skill and its documentation. Product references and generated campaign assets are managed separately as part of each outreach run.
