# My Resume Builder

The goal of this repo was to write my resume with asciidoc and automatically publish it to a host and generate a PDF 

![Resume Publishing](https://github.com/edenatx/resume/workflows/Publish%20Site/badge.svg)

## Why asciidoc?
You can use asciidoc to generate html and a pdf from the same file. 

It was mostly an idea for me to experiment with asciidoc and see what it could do.

## How to build?
Having the JVM is a pre-requisite. 

Run the following command to build the HTML 
`./gradlew asciidoctor`

Run the following command to build the pdf
`./gradlew asciidoctorPdf`

## How to access site that gets published?
https://edenatx.github.io/resume/
