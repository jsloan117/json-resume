# json-resume

My Resume

## How to use

hackmyresume BUILD resume.json /path/to/resume.pdf -t /path/to/theme/node_modules/jsonresume-theme-eloquent

## Selecting phantom or wkhtmltopdf

hackmyresume BUILD resume.json TO /path/to/resume.pdf -p (phantom|wkhtmltopdf) -t /path/to/theme/node_modules/jsonresume-theme-eloquent

## Manually creating PDF file, after editing the HTML file (if needed)

wkhtmltopdf /path/to/htmlfile/resume.pdf.html /path/to/output/resume.pdf

## Phantom example

phantom /path/to/htmlfile/resume.pdf.html /path/to/output/resume.pdf
