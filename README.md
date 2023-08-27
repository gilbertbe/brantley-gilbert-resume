# Brantley Gilbert's JSON Resume

After spending quite a bit of time trying to find the perfect resume template in Word I realized someone has to already have created a tool to allow people upload their resume info in a standardized way and export it in different formats. Lo and behold, [JSON Resume](https://jsonresume.org/) to the rescue!

To generate a PDF resume with my go-to format (assuming you have [npm](https://nodejs.org/) installed):
```shell
npm install -g resume-cli; # Install the JSON Resume CLI
npm install;               # Install the Kendall theme
resume export resume.pdf --theme kendall; # Generate PDF
```
