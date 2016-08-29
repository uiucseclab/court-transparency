# court-transparency

This is a project to allow for transparency and data mining of Champaign County court records.  The script (to be included) can be used by anyone to download a text copy of any court file docket or to download an entire year based on case type (i.e. 2015 Misdemeanors).

The directories contain the raw text files of those dockets that can be read directly.

The intent is to use data mining techniques to see what trends and patterns can be found in the administration of justice in Champaign County.

The script will prompt warnings when attempting to download a year's worth of case files during business hours but will only do so one case at a time regardless to minimize impact to the Circuit Clerk's systems.

# Prerequisites

The script is designed to run on a linux system and requires cURL and lynx.
