# Custom Reporting Widget Plugin Visualization Sample App

## Goal

The purpose of this sample Qualtrics Reporting Widget Plugin (**RWP**) is to make it easier for you to create your own custom RWP.

## Background

This sample Plugin contains code and configuration files that render a custom [interactive sunburst chart](https://observablehq.com/@d3/zoomable-sunburst) in a [Qualtrics CX dashboard](https://www.qualtrics.com/support/vocalize/getting-started-vocalize/vocalize-introduction/).

## Prequisites

1. Register as an XM Developer on the Qualtrics [Developer Portal](https://developer.qualtrics.com/)
2. [Create an XM Extension](https://developer.qualtrics.com/developer/portal/documentation/Step%201:%20Quick%20Start/hello-world.md)
3. [Create a RWP](https://developer.qualtrics.com/developer/portal/documentation/Step%201:%20Quick%20Start/z-reporting-widget-plugin.md)
4. [Dive into the details of RWP](https://developer.qualtrics.com/developer/portal/documentation/Step%203:%20Plugin%20Guides/reporting-widget.md)

## Setup

### Survey

1. Log into Qualtrics
2. Import the *nps.qsf* file, which is located in this directory, as a [new Survey Project](https://www.qualtrics.com/support/survey-platform/survey-module/survey-tools/import-and-export-surveys/#ImportingASurvey)
3. [Generate 500 test responses](https://www.qualtrics.com/support/survey-platform/survey-module/survey-tools/generating-test-responses/)

### Dashboard

1. Create a [new CX dashboard](https://www.qualtrics.com/support/vocalize/getting-started-vocalize/dashboard-overview/#CreatingYourFirstDashboard) or use an existing one
2. Map the **nps** survey [as a dataset to your dashboard](https://www.qualtrics.com/support/vocalize/getting-started-vocalize/pages-overview/#WhatsaDataSource)

### Plugin

1. Overwrite (if you haven't already) the files in your existing RWP directory (*/path/to/your/extension/plugins/your-rwp-plugin/*) with those contained in this package but **leave the other files/directories alone**
2. Run `npm install` on the command line
3. Run `npm start` on the command line
4. Follow these instructions [here](https://developer.qualtrics.com/developer/portal/documentation/Step%201:%20Quick%20Start/z-reporting-widget-plugin.md#step-2-run-your-extension) and then [here](https://developer.qualtrics.com/developer/portal/documentation/Step%201:%20Quick%20Start/z-reporting-widget-plugin.md#step-3-experience-your-extension) to render your RWP in a Qualtrics CX dashboard!

## Review

Review and set debug breakpoints in the code in order to better understand the logic and interactions between this sample RWP and the dashboard functionality.
