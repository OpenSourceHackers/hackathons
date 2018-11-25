# Hackathons

This project is aimed to list hackathons and their relative information.

## Contribution

Use the `template.json` file to see what fields and data are required.

```json
{
  "name": "REQUIRED",
  "description": "",
  "date": {
    "start": "REQUIRED",
    "end": "REQUIRED"
  },
  "location": "REQUIRED",
  "url": "REQUIRED",
  "prizes": [],
  "level": ['REQUIRED'],
  "attendees": []
}
```

1. Fork the project (top right of this page)
2. Clone your forked repo with `git clone URL_OF_YOUR_FORKED_REO`
3. Create a branch `git checkout -b BRANCH_NAME`
4. Add the hackathon event to the `hackathon.json` collection file with the required fields
5. Commit your changes `git commit -m "SHORT MESSAGE OF YOUR CHANGES" hackathon.json`
6. Push your changes to your forked repo `git push origin BRANCH_NAME`
7. Raise Pull Request on the original repo but select your forked repo and branch

Voila!
Any questions just ask us, we are friendly "Open Source Hackers"
