# Troubleshooting OnDemand

## Common problems

*coming soon*


## General information for troubleshooting OnDemand

Logs and scripts for each interactive session with Open OnDemand are stored in:

```
~/ondemand/data/sys/dashboard/batch_connect/sys
```

There are directories for each interactive app type within this directory. For example, to see the scripts and logs for an RStudio session, you might look at the files under:

```
~/ondemand/data/sys/dashboard/batch_connect/sys/rstudio/output/b5733507-a750-4bb9-8d4b-710618ce0de1
```

where `b5733507-a750-4bb9-8d4b-710618ce0de1` corresponds to a specific session of an OOD app (the RStudio app in this case).

## Getting Help
In case of questions, comments or issues get in touch with us. Please first collect all necessary details. In case of issues, this should include:

- Job ID and (if available) Session ID
- location of job scripts
- location of output/error files
- the full error message(s)
- your user name
- detailed description of expectation and observation
- Please open a ticket via [https://serviceportal.unibe.ch/hpc](https://serviceportal.unibe.ch/hpc).
