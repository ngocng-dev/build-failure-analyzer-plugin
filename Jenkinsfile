#!/usr/bin/env groovy

/* `buildPlugin` step provided by: https://github.com/jenkins-infra/pipeline-library */

@Library('pipeline-library') _

buildPlugin(
    platforms: ['linux'],
    findbugs: [run: true, archive: true],
    checkstyle: [archive: true, unstableTotalAll: 0]
  )
