#!/usr/bin/groovy

/*
This is a basic example for a Jenkins v4 pipeline

To learn how you can customize it for your project,
https://pipeline-doc.devops.jive.com/latest/contracts/pipeline/

To learn more about pipeline v4,
https://pipeline-doc.devops.jive.com
*/

@Library('jenkins-pipeline-library@release/3') _

// https://pipeline-doc.devops.jive.com/latest/contracts/pipeline/genericPipeline/
genericPipeline (
  metadata: [
    version: "v4",
    slack: [
      channel: "#pipeline-default"
    ]
  ]
  /*
  // Configure these blocks if using genericPipeline, otherwise remove them as other
  // [pipelines](https://pipeline-doc.devops.jive.com/latest/contracts/pipeline/)
  // already have a valid configuration.
  build: [
    // https://pipeline-doc.devops.jive.com/latest/contracts/object/vulnerabilityScan/
    vulnerabilityScan: [
        scanPatterns: ["set me"],
    ]
  ],
  deploy: [
    jira: [
      createTicket: true, // learn what the `createTicket` field means: https://pipeline-doc.devops.jive.com/latest/contracts/object/jira/
      teamName: '<team-name>',
      appName: '<app-name>',
    ]
  ]
  */
)
